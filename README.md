# WrenchAndRoll
Grease-monkey setup for total beginners. Get FreePascal (Geany/Lazarus) &amp; C/C++ builds rolling on Linux, Windows, and macOS. No diploma required—just grab your wrench and roll!


![WrenchAndRoll](WrenchAndRoll.jpg)


**WrenchAndRoll** — a greaser's toolkit for building my projects.  
Zero headaches. Single setup. Drop-in replacement for "I don't know how to compile this"  
without the confusion, without the dependency circus, without the RTFM.

**Dual toolchain:** Free Pascal and C/C++. Same spec. Two languages. Real builds.

---

![License](https://img.shields.io/badge/LICENSE-GPLV3-blue?style=for-the-badge)
![Language](https://img.shields.io/badge/LANGUAGE-FREE%20PASCAL%20|%20C%2FC%2B%2B-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/PLATFORM-LINUX%20|%20WINDOWS%20|%20MACOS-green?style=for-the-badge)
![Status](https://img.shields.io/badge/STATUS-WIP-red?style=for-the-badge)

---

## What is this?

Hey, code greaser! Don't know a compiler from a carburetor?  
This repo hot-rods your **Linux**, **Windows**, or **macOS** rig so you can build my FreePascal & C/C++ projects.  
Zero experience needed—just grab your wrench and roll!

---

## Toolchain by Platform

| OS | Free Pascal | C/C++ | IDE / Editor |
|---|---|---|---|
| **Linux** | `fpc` + `Geany` | `gcc`/`g++` + `Geany` | Geany |
| **Windows** | `Lazarus` + `fpc` | `gcc`/`g++` + `Geany` | Lazarus / Geany |
| **macOS** | `fpc` + `Geany` | `clang`/`clang++` + `Geany` | Geany |

---

## Quick Start

### Linux (Debian/Ubuntu)
```bash
sudo apt update
sudo apt install fpc geany gcc g++ make
# Clone any of my repos and build with Geany (Build → Compile)
