# main-db

`main-db` is the core Arabic content pack for the Al-Asl project. It contains structured JSON data for the Holy Quran and major hadith collections, intended to be consumed by the Android Al-Asl app as packaged source data.

## Overview

This repository provides the foundational Arabic text used by the application, with a focus on:

- Quran content in Arabic
- Sunni hadith collections
- A portable, app-friendly JSON structure
- Simple packaging metadata for integration into client apps

## Included content

The pack currently includes:

- Quran: `quran/ar/holy-quran.json`
- Hadith: `hadith/ar/abi-dawud.json`
- Hadith: `hadith/ar/bukhari.json`
- Hadith: `hadith/ar/ibn-majah.json`
- Hadith: `hadith/ar/muslim.json`
- Hadith: `hadith/ar/nasai.json`
- Hadith: `hadith/ar/tirmidhi.json`

## Repository structure

```text
main-db/
├── LICENSE
├── CREDIT
├── README.md
├── pack.json
├── hadith/
│   └── ar/
│       ├── abi-dawud.json
│       ├── bukhari.json
│       ├── ibn-majah.json
│       ├── muslim.json
│       ├── nasai.json
│       └── tirmidhi.json
└── quran/
    └── ar/
        └── holy-quran.json
```

## Pack metadata

The package configuration is defined in `pack.json` and includes:

- Pack ID: `org.al_asl.main_ar_core`
- Name: `Al-Asl Core Main Arabic Pack`
- Language: `ar`
- Type: `core`
- Version: `1.0.0`

## Usage

This repository is a data-only package. It is intended to be bundled into the app or loaded from an asset/resource directory so the application can parse the Quran and hadith JSON files at runtime.

## License

This project is licensed under the GNU General Public License v3.0. See `LICENSE` for details, and `CREDIT` for attribution information.
