# GraingerXML

> Public domain works of Percy Aldridge Grainger in MusicXML and MSCZ formats.

![GitHub stars](https://img.shields.io/github/stars/bonillamusic/GraingerXML?style=for-the-badge&logo=github) ![GitHub forks](https://img.shields.io/github/forks/bonillamusic/GraingerXML?style=for-the-badge&logo=github) ![GitHub issues](https://img.shields.io/github/issues/bonillamusic/GraingerXML?style=for-the-badge&logo=github) ![Last commit](https://img.shields.io/github/last-commit/bonillamusic/GraingerXML?style=for-the-badge&logo=github)

## 📑 Table of Contents

- [Description](#-description)
- [Key Features](#-key-features)
- [Use Cases](#-use-cases)
- [Quick Start](#-quick-start)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Public Domain Notice](#public-domain-notice)

## 📝 Description

GraingerXML is a dedicated digital archive containing the public domain musical works of composer Percy Aldridge Grainger (1882-1961). The repository solves the problem of finding clean, structured, and machine-readable digital scores of his compositions, making them easily accessible for modern performances, study, and digital preservation.

At this time, the archive includes a digitized edition of Grainger's "Two Musical Relics of My Mother" in both MusicXML and MSCZ formats, with plans to expand the library over time.

## ✨ Key Features

- **🎼 MusicXML Score Archive** — Provides open-standard MusicXML files that are highly compatible with most modern notation software and digital sheet music readers.
- **🎹 MSCZ MuseScore Studio Score Archive** — Includes MSCZ files for native editing, layout adjustments, and MIDI playback directly within the MuseScore Studio application.
- **📂 Clear repository layout** — Each format is stored in a dedicated top-level folder so visitors can quickly locate source files and sample scores.

## 🎯 Use Cases

- Musicians wanting to study, rehearse, or perform digitized scores of Percy Aldridge Grainger's compositions.
- Music theorists and researchers performing computational musicology analysis on structured MusicXML data.
- Composers and arrangers seeking editable digital files to adapt or rearrange Grainger's works for different ensembles.
- Archivists and digital librarians reviewing an emerging public domain score archive and planning future contributions.

## 🚀 Quick Start

1. Clone the repository: `git clone https://github.com/bonillamusic/GraingerXML.git`
2. Open `MusicXML/Two Musical Relics of My Mother.musicxml` in notation software such as MuseScore, Dorico, Finale, or any MusicXML-compatible editor.
3. Open `MSCZ/Two Musical Relics of My Mother.mscz` directly in MuseScore for native editing and playback.
4. Explore `roadmap.md` for planned additions, curation notes, and the current development roadmap.

## 📁 Project Structure

```
.
├── LICENSE
├── README.md
├── MSCZ
│   └── Two Musical Relics of My Mother.mscz
├── MusicXML
│   └── Two Musical Relics of My Mother.musicxml
└── index.csv
```

## 👥 Contributing

Contributions are welcome! Here's the standard flow:

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/bonillamusic/GraingerXML.git`
3. **Branch**: `git checkout -b feature/your-feature` (score in musicXML format)
4. **Commit**: `git commit -m 'feat: add some feature'`
5. **Push**: `git push origin feature/your-feature`
6. **Open** a pull request

There are currently folders for .musicXML and .mscz file formats, but we are open to accepting scores in other software formats! (This also allows for more proprietary formatting to be preserved which is otherwise lost in the conversion to musicXML). Please use the uncompressed form (.musicXML) and NOT the compressed form (.mxl) for submissions.

## 📜 License

This project is licensed under the **CC0-1.0** License.

## Public Domain Notice
From IMSLP:

Works by this person are generally in the public domain in Canada. Works by this person are not in the public domain in countries with a life+70 copyright term (including all EU countries), unless an exception applies. In the United States, all works first published before 1931 are in the public domain; works first published afterwards may be protected by copyright. See [public domain](https://imslp.org/wiki/Public_domain) for more information.

**Works by this person may not be in the public domain in all countries. Please check the copyright laws of your country.**
---
*This README was generated with ❤️ by [ReadmeBuddy](https://readmebuddy.com)*
