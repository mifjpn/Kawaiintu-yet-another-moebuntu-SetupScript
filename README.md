# 🌈 Kawaiintu (Post-Moebuntu) Setup Helper

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Ubuntu 26.04 LTS](https://img.shields.io/badge/Ubuntu-26.04%20LTS-E95420?logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![GitHub Stars](https://img.shields.io/github/stars/mifjpn/Kawaiintu-yet-another-moebuntu-SetupScript?style=social)](https://github.com/mifjpn/Kawaiintu-yet-another-moebuntu-SetupScript)

> The legitimate successor to Moebuntu. A safe, smart, and above all, **KAWAII** Ubuntu customization tool.

**English** | [日本語](#-kawaiintu-post-moebuntu-setup-helper)

---

## 🎯 What is Kawaiintu?

Kawaiintu inherits the spirit of the nostalgic **Moebuntu** while providing full support for the latest Ubuntu 26.04 LTS, as the next-generation Ubuntu customization tool.

### 🌟 Recommended for:

- 📌 **Those with Moebuntu memories** → Recreate nostalgia with evolved cuteness
- 🎨 **Want to make Ubuntu cuter** → Customize with 9 beautiful color themes
- 🛡️ **Want to use it with peace of mind** → Safe design that never breaks your system
- 💻 **Want to run on the latest Ubuntu** → Fully compatible with Ubuntu 26.04 LTS

---

## 🎬 Watch It in Action!

### ✨ Color Theme Switching Demo

[![Kawaiintu Theme Demo](https://img.youtube.com/vi/FO4BmporPio/maxresdefault.jpg)](https://www.youtube.com/shorts/FO4BmporPio)

**[Watch on YouTube Shorts →](https://www.youtube.com/shorts/FO4BmporPio)**

---

## 🎨 9 Beautiful Color Themes

<img src="https://raw.githubusercontent.com/mifjpn/Kawaiintu-yet-another-moebuntu-MifjpnsOriginal/main/themes/background.jpg" width="600" alt="Kawaiintu Theme Background">

Kawaiintu features **9 sophisticated color variations**.  
Switch to a perfectly unified kawaii world with just one click.

---

## ✨ What's New in Kawaiintu!

### 🎓 Evolved "Sophisticated Kawaii"
Transitioning from the overly sweet design of traditional Moebuntu to a more refined, "clean and cute" aesthetic. Modern elegance that is easy to use for daily tasks.

### 🔧 Fully Automated (Python-driven)
- Everything from color generation to setup is automated
- No manual work in Illustrator required
- Dangerous hardcoded settings are completely eliminated
- **Safe, Easy, and Reliable**

### 🛡️ Safe and Secure Design
Designed to absolutely never break system files. No more worrying about "messing up your PC" when customizing.

### 📁 Unified, Beautiful Icons
Eliminated the mixture of line art and color icons in the file manager. Everything is now harmonized with matching color schemes.

### 🎨 Fully Applied Application Themes
Automatically applies the system theme to modern applications like GIMP. The kawaii aesthetic is maintained even when you open apps.

### 🖼️ Super Easy Login Screen Customization
No complicated configuration files needed. Just drag & drop your favorite image, and Kawaiintu will automatically apply it to the login screen.

### 🚀 Fully Compatible with Ubuntu 26.04 LTS
Optimized for the latest GNOME desktop environment. All the latest features are fully supported.

---

## 🚀 Quick Start

### Requirements
- **Ubuntu 26.04 LTS** (Optimized for this version)

### Installation Guide

#### 1️⃣ Download
From your browser, go to the [Release](https://github.com/mifjpn/Kawaiintu-yet-another-moebuntu-SetupScript/releases/tag/v1.0.0) page and download `scripts.tar.xz`.

#### 2️⃣ Extract
Double-click `scripts.tar.xz` or use the archive manager to extract it.

#### 3️⃣ Run
Open the extracted `scripts` folder, right-click `Kawaset` → select **"Run as a Program"**!

🎉 The **Kawaiintu Setup Helper** menu will open.

---

## 📖 How to Use (Details)

### ⚠️ MUST READ: Always start with "base setting (Do first!)"

When the menu opens, please execute "base setting (Do first!)" first.

This step will open `gnome-shell-extension-manager`:

1. Search for "User Themes" in the **"Browse"** tab
2. Click **"Add"** to install
3. Move to the **"Installed"** tab and toggle **"User Themes"** to **ON**
4. Close the window

✅ After this setup, themes will be applied correctly.

### 🎨 Apply Themes

#### Color Theme
Just choose your favorite color from the menu. Window themes and Shell themes will be applied automatically.

#### 🖼️ Login Screen (GDM) Customization
You can also customize the login screen while applying a theme:

- Enter `Y` to change the login screen
- **Drag & drop your favorite image file** → Automatically converted and applied
- Alternatively, select Kawaiintu's default kawaii illustration or a simple black background

#### 🎨 Icons
Easily apply or remove Kawaii icon packs.

#### 🥾 Plymouth (Boot Screen)
Set up a kawaii spinner screen for OS boot. Custom images can also be used.

#### 🖥️ Wallpaper
Freely customize your desktop background. Supports drag & drop. Automatically applied to both Light and Dark modes.

### 🔌 Application Settings

#### Firefox
- Switch between Snap and Deb versions (Deb version is recommended)

#### File Manager
- Install, configure, or remove **Nemo** / **Thunar**
- Includes custom action presets, such as "Open in Terminal"

#### Media Player
- Easily remove unnecessary apps like VLC

### 🔊 Sound

Choose from multiple Kawaii sound themes:
- Amateur Voice Actor version
- Maid version
- Sci-Fi version
- Hatsune Miku version
- And more

Easy removal of custom sounds.

### 🔄 Revert to Default

Select **"remove Kawaiintu/Moe-theme"** to safely remove all customizations and revert to the default Ubuntu (Yaru) theme.

---

## ⚠️ Known Issues

### User Themes Extension in VirtualBox Environments
In very rare cases, the User Themes extension may not become active immediately.

**Solution:** Apply it manually from GNOME Tweaks or restart the system.

### Issues After Ubuntu Upgrades
If you upgraded Ubuntu without doing a clean install, the initial setup might fail.

**Solution:**
```bash
sudo apt remove gnome-shell-extension-manager
sudo apt install gnome-shell-extension-manager
```

After doing this, please run the base setup again.

---

## 🌍 Community

We're waiting for your feedback to make Kawaiintu even better!

- **🐛 [GitHub Issues](https://github.com/mifjpn/Kawaiintu-yet-another-moebuntu-SetupScript/issues):** Bug reports & feature requests
- **💬 [GitHub Discussions](https://github.com/mifjpn/Kawaiintu-yet-another-moebuntu-SetupScript/discussions):** General chat, usage examples, customization sharing
- **📹 [YouTube Shorts](https://www.youtube.com/shorts/FO4BmporPio):** Check out demo videos for operational flow

### ⭐ Like this project?

[Give us a Star on GitHub!](https://github.com/mifjpn/Kawaiintu-yet-another-moebuntu-SetupScript/stargazers) 😍  
More stars = More visibility!

---

## 📝 License & Developer Info

This setup helper is released under the **MIT License**.

**Feel free to fork, modify, and translate it!** Please go ahead and create a version in your local language.

### Credits
- **Core Themes, Plymouth, Icons:** Toy (Original Creator of Moebuntu)
- **Kawaiintu Transformation, Automation System, Python Compilation:** Mifjpn

### Important Request
When forking, please do not include theme files directly in the repository. Set them up to be dynamically downloaded from GitHub.

---

## 💝 Respect for Moebuntu

Kawaiintu is the legitimate successor that brings the nostalgic Moebuntu into the latest Ubuntu environment (26.04 LTS) with love and respect.

We have evolved the "Kawaii Ubuntu" worldview created by Moebuntu into something safer, smarter, and easier for everyone to use.

Enjoy the newly reborn, safe, and smart world of Kawaiintu! 🌈✨
