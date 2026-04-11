# 🛠️ A&S RTX Patcher — External Tools & Actions Stuff

This repository contains auxiliary tools and GitHub Actions utilities that support the **A&S Minecraft RTX Community Patcher** but don't belong in the main patcher branch.

> 🔗 **Main project:** [A&S Minecraft RTX Community Patcher](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher)

---

## 📦 What's in here?

### `brachiveextractor/`
A standalone tool for extracting and parsing **Brarchive** (`.brarchive`) files used by Minecraft RTX resource packs.  
Includes a GUI-based extractor with support for encrypted and versioned archive formats.

Key files:
- `main.py` — Entry point with the GUI
- `extractor_core.py` — Core extraction logic
- `brarchive_format.py` — Archive format parsing
- `build.bat` — Convenience script to build the standalone executable via PyInstaller

---

### `create_patch_v2.py`
A patch creation utility (v2) used to generate xdelta3-based patch files for the RTX patcher pipeline.

---

## 🤝 Relation to the Main Patcher

The [A&S Minecraft RTX Community Patcher](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher) is the core project. This repo exists to keep the main branch clean by housing:

- **CI/CD helpers** and GitHub Actions scripts
- **Standalone tools** used during the build/release process
- **Experimental or supporting utilities** not part of the patcher runtime

---

## 📄 License

See [LICENSE](./LICENSE) for details.