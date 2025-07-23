# 🤖 Assistant.AI - WhatsApp Multi-Tool Bot

![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/assistant-ai)
![GitHub license](https://img.shields.io/github/license/yourusername/assistant-ai)
![Maintenance](https://img.shields.io/badge/maintained-yes-brightgreen)

> Bot WhatsApp powerful berbasis Baileys MD yang dilengkapi fitur AI, hiburan, alat media, tools admin, hingga fitur Islami.

---

## 🧠 Tentang Project

Assistant.AI adalah bot WhatsApp serbaguna yang dibuat dengan **JavaScript (Node.js)** menggunakan library **Baileys**. Cocok digunakan untuk hiburan, edukasi, atau bahkan untuk keperluan komunitas/grup Anda.

---

## 🚀 Fitur Utama

### 📱 Menu Utama
- `.menu` – Menampilkan daftar menu interaktif
- `.aimenu` – Fitur AI seperti ChatGPT, translate, image gen
- `.funmenu` – Tebak gambar, prank, suit, dll
- `.islamicmenu` – Jadwal sholat, niat sholat, doa harian
- `.toolmenu` – Media downloader, ocr, kode warna

### 🤖 Fitur AI
- ChatGPT Chat (tanpa API key)
- Text to Image (stable diffusion)
- Translator AI

### 🎮 Games
- Suit Jepang, Math Game, Tebak Gambar, Tebak Lagu
- Random Jokes, Truth or Dare

### 🎥 Media Tools
- YouTube MP3/MP4 Downloader
- Instagram Reels Downloader
- Pinterest Search, Image OCR

### 🕌 Fitur Islami
- Doa Harian, Niat Sholat
- Jadwal Sholat otomatis (berdasarkan lokasi)
- Al-Quran per surah

### 👮 Admin & Utility
- Anti Spam, Anti Link, Mode Public/Private
- Broadcast, Statistik penggunaan
- Typo detection & auto-correct command (optional)

---

## 📁 Struktur Folder

```bash
├── lib/
│   ├── functions.js
│   └── db.json
├── src/
│   ├── media/
│   └── plugins/
├── index.js
├── config.json
└── README.md
```

---

## 🛠 Customisasi

Semua file command terdapat di `case.js`. Kamu bisa mengubah nama case, menambah command baru, atau mengedit tampilan menu.

```js
{
  title: '🔥 Menu Paling Populer',
  rows: [
    { title: '🎉 Fun Menu', description: 'Menu hiburan lucu-lucuan dan prank', id: `${prefix}funmenu` },
    { title: '🎮 Game Menu', description: 'Main game bareng bot, suit, tebak, dll', id: `${prefix}gamemenu` },
    { title: '🤖 AI Menu', description: 'ChatGPT, Translate, Image AI', id: `${prefix}aimenu` }
  ]
}
```

---

## 🙏 Terima Kasih

Bot ini terinspirasi dan dibangun dari berbagai open source:
- [Baileys MD](https://github.com/WhiskeySockets/Baileys)
- [Nekorinn API](https://api.nekorinn.my.id)
- [Zenz API](https://zenz.biz.id)

---

## 📜 Lisensi

MIT License © 2025 – [pashaba](https://github.com/pashaba)
