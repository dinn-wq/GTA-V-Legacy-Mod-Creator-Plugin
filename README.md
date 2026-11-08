# GTA V Legacy Mod Creator

An open-source ChatGPT plugin source package for designing, generating, packaging, troubleshooting, and maintaining **GTA V Legacy Story Mode** mods on Windows PC.

> This repository contains the **ChatGPT plugin source**, not a precompiled GTA V mod.

## Version

**v1.2.3**

## What it can do

- Generate GTA V Legacy Story Mode mod ideas
- Quick Mod Generator
- Mod Recommendation
- One-by-One Mod Builder
- Mod Installation Advisor
- GTA-style mission structure and UI guidance
- Packaging and troubleshooting guidance
- Anti-cheat safeguards
- Beginner-friendly install explanations

## Model recommendation

- **GPT-6** is recommended when available for larger or more complex mod projects.
- If GPT-6 is not available, use **GPT-5.6 or higher** for better consistency with APIs, dependencies, multi-file code, and debugging.
- Lower-capability models may need extra review.
- Model choice does **not** replace compiling, dependency checks, or in-game testing.

## Target

- Grand Theft Auto V Legacy
- Windows PC
- Steam is the primary testing target
- Story Mode / offline

Do not use Story Mode script modifications in GTA Online.

## Repository structure

```text
GTA-V-Legacy-Mod-Creator-v1.2.3/
├── plugin.json
├── .codex-plugin/
│   └── plugin.json
├── assets/
│   └── gta-v-legacy-mod-creator.png
├── skills/
│   ├── gta-v-legacy-mod-creator/
│   ├── mod-installation-advisor/
│   ├── mod-recommendation/
│   ├── one-by-one-mod-builder/
│   └── quick-mod-generator/
├── CHANGELOG.md
├── LICENSE
├── VERSION.txt
└── README.md
```

## How to use

1. Download or clone this repository.
2. Use the repository as the source for your own ChatGPT plugin project.
3. Keep the folder structure intact.
4. Review `plugin.json` before importing or publishing your own copy.
5. Update the author/developer metadata if you fork and redistribute it under your own identity.

## Important

This project does not bundle Script Hook V, ScriptHookVDotNet, NativeUI, OpenIV, GTA V files, or other third-party software.

The plugin may generate source code, but generated code should still be reviewed, compiled with the correct dependencies, and tested in GTA V Legacy Story Mode.

## Safety

The included skills are designed for fair Story Mode mod development and do not support cheat trainers, anti-cheat bypasses, exploit automation, or multiplayer advantage tools.

## License

MIT License. See `LICENSE`.
