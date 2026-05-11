<table>
<tr>
<td width="140" align="center">
<img width="120" alt="A&S RTX Patcher Logo" src="https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher/raw/main/A%26S%20Patcher/assets/resources/as_rtx_simple_logo_.png" />
</td>
<td>

## A&S RTX Patcher — External Tools

*Auxiliary tools and utilities for the A&S RTX Community Patcher*

[![Main Patcher](https://img.shields.io/badge/Main_Patcher-Actions--and--Stuff--RTX--Patcher-2ea44f?style=flat-square&logo=github)](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher)
[![Discord](https://img.shields.io/discord/1432653252171661364?logo=discord&style=flat-square&label=Discord)](https://discord.gg/YrMMmN2kc7)

</td>
</tr>
</table>

---

- 🔧 Houses tools that support the patcher but **don't belong in the main branch**
- 📦 Includes the **Brarchive Extractor** for unpacking Minecraft resource archives
- 🛠️ Contains the **Patch Creator v2** for generating xdelta3-based patches

> [!IMPORTANT]
> This is a **companion repository**. For downloads, releases, and documentation, head to the **[Main Patcher Repo →](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher)**

---

## 📁 Repository Overview

| Repository | Description | Link |
| :--- | :--- | :---: |
| **A&S RTX Patcher** | Main patcher — Marketplace & Zip support, GUI, automated patching | [Repo](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher) |
| **Archive** | All binary patch files and legacy V1 patcher source | [Repo](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher-Archive) |
| **External Tools** | Brarchive extractor, and other tools for the patcher! | **This Repo** |

---

## 📦 What's in This Repository?

### `brachiveextractor/`

A standalone tool for extracting and parsing **Brarchive** (`.brarchive`) files used by Minecraft RTX resource packs.
Includes a GUI-based extractor with support for encrypted and versioned archive formats.

| File | Purpose |
| :--- | :--- |
| `main.py` | Entry point with the GUI |
| `extractor_core.py` | Core extraction logic |
| `brarchive_format.py` | Archive format parsing |
| `build.bat` | Build standalone `.exe` via PyInstaller |

---

### `create_patch_v2.py`

A patch creation utility used to generate **xdelta3-based** `.vcdiff` patch files for the RTX patcher pipeline. This is used internally to create new patches when A&S updates are released.

---

### Test Files

| File | Purpose |
| :--- | :--- |
| `_test_brarchive.py` | Unit tests for Brarchive format parsing |
| `_test_extractor_core.py` | Unit tests for the extraction logic |

---

> [!NOTE]
> **Disclaimer:** This project is community-built for personal & educational use only. It is not affiliated with or endorsed by Oreville Studios or Mojang/Microsoft.

---

## 📄 License

See [LICENSE](./LICENSE) for details.