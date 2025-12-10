<div align="center">

# 💌  Sanjay's Arch - Hyprland Install Script 💌
<p align="center">
  <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/e2401f91-f0dd-4f23-b749-3e9abc2f171c/dfwsxdb-074d0db3-a59c-4499-b56f-8515bd91a194.png/v1/fill/w_1280,h_723,q_80,strp/arch_linux_blue_and_green_wallpaper_by_moonditto_dfwsxdb-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9NzIzIiwicGF0aCI6Ii9mL2UyNDAxZjkxLWYwZGQtNGYyMy1iNzQ5LTNlOWFiYzJmMTcxYy9kZndzeGRiLTA3NGQwZGIzLWE1OWMtNDQ5OS1iNTZmLTg1MTViZDkxYTE5NC5wbmciLCJ3aWR0aCI6Ijw9MTI4MCJ9XV0sImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl19.pF55rIGOpOUW3vMvkMENmtasYtwiXpkKaO7HqLRepVI" width="900">
</p>

**A customized Hyprland installation script for Arch Linux.**

</div>

## 📋 Description

This repository contains scripts to install and configure Hyprland on Arch Linux, customized with my personal dotfiles and settings. It streamlines the process of setting up a fully functional and aesthetic desktop environment.

## 🚀 Installation Instructions

### 1. Auto-Install (Recommended)

The easiest way to install is using the auto-install script. Run the following command in your terminal:

```bash
sh <(curl -L https://raw.githubusercontent.com/sanjayrohith/Arch-Hyprland/main/auto-install.sh)
```

### 2. Manual Installation

If you prefer to inspect the code or install manually:

```bash
git clone --depth=1 https://github.com/sanjayrohith/Arch-Hyprland.git ~/Arch-Hyprland
cd ~/Arch-Hyprland
chmod +x install.sh
./install.sh
```

## 📂 What's Included?

- **Hyprland**: The window manager itself.
- **Dotfiles**: Configurations for Hyprland, Waybar, Kitty, Rofi, etc. (pulled from [sanjayrohith/Hyprland-Dots](https://github.com/sanjayrohith/Hyprland-Dots)).
- **Themes**: GTK themes and icons (pulled from [sanjayrohith/GTK-themes-icons](https://github.com/sanjayrohith/GTK-themes-icons)).
- **Shell**: Zsh configuration with plugins.

## ⚠️ Important Notes

- **Backup**: Always backup your important data before running installation scripts.
- **Base System**: This script is best run on a minimal Arch Linux installation.

## 🤝 Credits & Acknowledgements

- **Original Author**: [JaKooLit](https://github.com/JaKooLit) - This project is a fork of his amazing work.
- **Customized by**: Sanjay
