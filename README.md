<div align="center">

# 💌 ** Sanjay's Arch - Hyprland Install Script ** 💌

<p align="center">
    <img src="https://raw.githubusercontent.com/sanjayrohith/Hyprland-Dots/main/assets/latte.png" width="400" />
</p>

**A customized Hyprland installation script for Arch Linux.**

</div>

## 📋 Description

This repository contains scripts to install and configure Hyprland on Arch Linux, customized with my personal dotfiles and settings. It streamlines the process of setting up a fully functional and aesthetic desktop environment.

## 🚀 Installation Instructions

### 1. Auto-Install (Recommended)

The easiest way to install is using the auto-install script. Run the following command in your terminal:

```bash
sh <(curl -L https://raw.githubusercontent.com/sanjay_rohith/Arch-Hyprland/main/auto-install.sh)
```

### 2. Manual Installation

If you prefer to inspect the code or install manually:

```bash
git clone --depth=1 https://github.com/sanjay_rohith/Arch-Hyprland.git ~/Arch-Hyprland
cd ~/Arch-Hyprland
chmod +x install.sh
./install.sh
```

## 📂 What's Included?

- **Hyprland**: The window manager itself.
- **Dotfiles**: Configurations for Hyprland, Waybar, Kitty, Rofi, etc. (pulled from [sanjay_rohith/Hyprland-Dots](https://github.com/sanjay_rohith/Hyprland-Dots)).
- **Themes**: GTK themes and icons (pulled from [sanjay_rohith/GTK-themes-icons](https://github.com/sanjay_rohith/GTK-themes-icons)).
- **Shell**: Zsh configuration with plugins.

## ⚠️ Important Notes

- **Backup**: Always backup your important data before running installation scripts.
- **Base System**: This script is best run on a minimal Arch Linux installation.

## 🤝 Credits & Acknowledgements

- **Original Author**: [JaKooLit](https://github.com/JaKooLit) - This project is a fork of his amazing work.
- **Customized by**: Sanjay
