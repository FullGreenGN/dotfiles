# 🚀 My Arch Linux Dotfiles

Welcome to my personal dotfiles repository. This contains the configuration files for my daily driver setup, heavily focused on a smooth Wayland experience.

## 🖥️ System Overview

- **OS:** Arch Linux
- **Compositor:** Hyprland (Wayland)
- **Terminal:** Kitty
- **File Manager:** Dolphin
- **System Monitor:** Btop

## 📦 What's Included

Here is a breakdown of the configurations backed up in this repository:

- **`hypr/`**: Core Hyprland configuration, window rules, and keybindings (including resize mappings and XWayland Video Bridge fixes).
- **`kitty/`**: Terminal emulator settings.
- **`btop/`**: Resource monitor configuration.
- **`easyeffects/`**: Audio processing and equalization.
- **`gtk-3.0/` & `gtk-4.0/` & `nwg-look/`**: GTK application theming.
- **`qt5ct/` & `qt6ct/`**: Qt application theming.
- **`ambxst/`**: Base themes and aesthetic settings.

## 🛠️ Installation

To deploy these dotfiles on a new machine, clone this repository and create symlinks to your `~/.config` directory. 

Example:
```bash
git clone [https://github.com/FullGreenGN/dotfiles.git](https://github.com/FullGreenGN/dotfiles.git) ~/dotfiles
ln -s ~/dotfiles/hypr ~/.config/hypr
