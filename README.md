# ⚔️ World of Warcraft 3.3.5a Asset Explorer

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://elwynsiaa.github.io/wow-3.3.5a-asset-explorer/)
[![Files Indexed](https://img.shields.io/badge/Files%20Indexed-204%2C348-blue)](#)
[![Client Version](https://img.shields.io/badge/WoW-3.3.5a%20(12340)-orange)](#)

A fast, searchable web-based file browser and asset database for **World of Warcraft: Wrath of the Lich King (3.3.5a)**.

🌐 **Live Demo:** [https://elwynsiaa.github.io/wow-3.3.5a-asset-explorer/](https://elwynsiaa.github.io/wow-3.3.5a-asset-explorer/)

---

## ✨ Features

* 🔍 **Instant Search:** Search across **204,000+** extracted client files in milliseconds.
* 🎯 **Dynamic File Type Filter:** Automatically detects and filters by extensions (`.blp`, `.m2`, `.skin`, `.dbc`, `.wav`, `.ogg`, `.adt`, `.wmo`, etc.).
* 👁️ **In-Browser BLP Decoder:** Native JavaScript texture decoder to inspect `.blp` images directly inside your browser (supports DXT1, DXT3, DXT5, and ARGB8888).
* ⚡ **High Performance:** Memory-optimized compressed JSON index with deferred DOM rendering.
* 📦 **Zero Backend:** Hosted entirely on GitHub Pages via GitHub Actions workflow deployment.

---

## 📁 Covered Asset Categories

Contains the complete extracted contents of all 3.3.5a MPQs (`common`, `expansion`, `lichking`, and locale patches):

* `Character/` - Player models, hair, facial features, armor textures
* `Creature/` - NPC/Monster models, skins, and textures
* `DBFilesClient/` - Client database files (`.dbc`)
* `Item/` - Item textures, icon graphics, equipment models
* `Sound/` - Music, ambient audio, character voice lines
* `Interface/` - UI textures, icons, frame graphics
* `World/` - Environment maps, doodads, terrain textures, WMO buildings

---

## 🛠️ Built With

* [DataTables](https://datatables.net/) - High-performance table rendering
* [jQuery](https://jquery.com/) - DOM manipulation
* **Native JavaScript BLP Decoder** - Zero-dependency DXT texture decoder
* **GitHub Actions & Pages** - Automated static deployment pipeline

---

## ⚖️ Disclaimer

World of Warcraft, Wrath of the Lich King, and all associated assets, textures, models, and audio are copyrighted trademarks of **Blizzard Entertainment**. This project is strictly for educational, research, and community modding reference purposes.
