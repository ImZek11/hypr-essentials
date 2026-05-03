# Hypr Essentials ⚙️

A clean, organized, and out-of-the-box foundation for Hyprland.

## 📌 Overview
**Hypr Essentials** is a minimalist starting point for anyone who wants the default Hyprland experience without the clutter. It provides a structured configuration environment and full **Noto Fonts** integration to ensure all emojis and special characters work perfectly from the first boot.

This repository doesn't change the look or feel of the original Hyprland; it simply organizes the "behind the scenes" so you can start building your setup on a rock-solid, "vanilla" base.

## ✨ Key Features
*   **Organized Structure:** Modular configuration files for easier maintenance.
*   **Full Emoji Support:** Pre-configured with Noto Fonts (Emoji, CJK, and Standard).
*   **Vanilla Experience:** No unnecessary bloat, custom themes, or forced aesthetic changes.
*   **Easy Installation:** Includes a streamlined script to get you up and running on Arch Linux.

## 📂 Repository Structure
The configuration is split into logical modules to keep your `hyprland.conf` clean:
```text
hypr/
├── hyprland.conf          # Main entry point
└── modules/               # Modularized settings
    ├── animations.conf    # Window animations and transitions
    ├── autostart.conf     # Apps that run on launch (Waybar, etc.)
    ├── env.conf           # Environment variables
    ├── input.conf         # Keyboard and touchpad settings
    ├── keybindings.conf   # Keyboard shortcuts
    ├── layout.conf        # Dwindle/Master layout settings
    ├── look.conf          # General aesthetics (borders, gaps, colors)
    ├── monitor.conf       # Display and resolution settings
    ├── mouse.conf         # Specific mouse sensitivity/acceleration
    ├── programs.conf      # Default app definitions (Terminal, File Manager)
    └── windowrules.conf   # Specific rules for app windows
```

## 🚀 Installation

> [!IMPORTANT]
> This script is designed for **Arch Linux**.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ImZek11/hypr-essentials.git
   cd hypr-essentials
   ```

2. **Make the script executable:**
   ```bash
   chmod +x install.sh
   ```

3. **Run the installer:**
   ```bash
   ./install.sh
   ```

## 🛠️ Included Packages
To ensure a functional "out-of-the-box" experience, the installer includes:
- **Hyprland:** The compositor itself.
- **Kitty:** The default terminal.
- **Waybar:** For a clean status bar.
- **Noto Fonts:** Standard, Emoji, and CJK support.
- **XDG Portals:** For screen sharing and compatibility.
- **Nautilus:** The intuitive GNOME file manager.
- **Neovim:** A powerful, extensible text editor.

## 📄 License
This project is licensed under the [MIT License](LICENSE).
