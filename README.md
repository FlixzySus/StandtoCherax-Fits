# Stand to Cherax Outfit Converter

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](#)
[![License](https://img.shields.io/badge/license-MIT-blue)](#)
[![Platform](https://img.shields.io/badge/platform-Windows-lightgrey)](#)
[![Cherax Compatible](https://img.shields.io/badge/cherax-supported-purple)](#)

A custom GTA V tool that converts **Stand mod menu `.txt` outfit files** into **Cherax-compatible `.json` outfit files**

---

# Important!

`When loading outfit saves with glasses in Cherax(glasses will stick to character after loading a different save).`

`A bug in cherax(manually reset glasses appearence) in Cherax>Player>Cosmetic>Props(select glasses and apply values to -1) `

---

## 💾 How to Use

### 🧷 Step 1: Download

Downloaded the latest `StandtoCheraxFits.exe`

---

### 📁 Step 2: Required Files

Place these **in the same folder** as the EXE:

- `CheraxMale.json`
- `CheraxFemale.json`
- `Male_Component_Texture_Counts.csv`
- `Female_Component_Texture_Counts.csv`
- `Male_Prop_Texture_Counts.csv`
- `Female_Prop_Texture_Counts.csv`

---

### 🚀 Step 3: Run the App

1. Double-click `StandtoCheraxFits.exe`
2. Click **“Load Stand Outfit 📂”** and select the root folder containing sub-folders with `.txt` outfits inside
3. Click **“🚀 Convert to Cherax JSON”**
4. Converted `.json` files will appear inside:

     ```
     Cherax_<SelectedRootFolder>/
     ├── <SubfolderName>/
     │   └── Cherax_file1.json
     └── <AnotherSubfolder>/
         └── Cherax_file2.json
     ```

---

## ✨ Features

- ✅ **Batch Conversion**: Processes entire folders of `.txt` Stand outfit files
- ✅ **Auto Gender Detection**: Detects whether if save is `Male` or `Female`
- ✅ **Cherax Accuracy**: Uses correct component & prop texture counts `Made by yours truly`
- ✅ **Validated Output**: Auto-corrects invalid texture indexes
- ✅ **GUI**: Gradient interface with real-time logging
- ✅ **Portable EXE**: No Python install required to run

---

## 💬 Credits

- Created by **Bunny**  
- Discord `.itsBunny` 💜

---
