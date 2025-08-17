# Disable Built-in Keyboard

A simple Bash script to disable the built-in laptop keyboard on Linux systems using `xinput`.

## 📋 Description

This script searches for the built-in keyboard device (specifically named **"AT Translated Set 2 keyboard"**) and disables it using the `xinput` utility. It's useful in scenarios where you want to prevent unintended keystrokes from the internal keyboard — such as when using an external keyboard.

## ✅ Requirements

- Linux OS with X server running
- `xinput` installed

You can install `xinput` using your package manager:

```bash
# Debian/Ubuntu
sudo apt install xinput

# Fedora
sudo dnf install xinput

# Arch
sudo pacman -S xorg-xinput

