# Kawaiintu (Post-Moebuntu) Setup Helper
Setup Helper Script for Repository: Kawaiintu-yet-another-moebuntu-MifjpnsOriginal

<img src="https://raw.githubusercontent.com/mifjpn/Kawaiintu-yet-another-moebuntu-MifjpnsOriginal/main/themes/background.jpg" width="600" alt="Kawaiintu Theme Background">

## 1. Overview of this setup helper
This setup helper is designed for the "[mifjpn/Kawaiintu-yet-another-moebuntu-MifjpnsOriginal](https://github.com/mifjpn/Kawaiintu-yet-another-moebuntu-MifjpnsOriginal)" repository.

Kawaiintu (Post-Moebuntu) represents a modernized, highly automated evolution that moves beyond the legacy, hard-coded configurations of traditional Moebuntu. The repository features a collection of beautifully crafted kawaii (moe) color themes, Plymouth boot screens, and cute system sounds.
This setup helper (`Kawaset`) takes the hassle out of manual configurations and allows you to easily apply, customize, and manage these adorable system environments with a smart, interactive menu.

## 2. How to use

**Note: Although the internal mechanics have been completely modernized, the basic usage remains largely unchanged from the Moebuntu era. If you are familiar with Moebuntu, you will feel right at home!**

### 1) Operating system environment, download and preparation.
Please prepare **Ubuntu 26.04 LTS**. This script is optimized for this OS version.
First, download the release archive `scripts.tar.xz` using your web browser.
Extract this file using "Archive Manager" or your preferred extraction tool.
Once the `scripts` folder is unpacked, you will find all the helper scripts inside.

### 2) Explanation of the simplest usage
Open the extracted `scripts` folder in your file manager (e.g., Nautilus or Thunar).
The main script you need to run is **`Kawaset`**.
The easiest way is to right-click on `Kawaset` and select **"Run as a Program"** (or execute it directly from the terminal).
When the script runs, the **Kawaiintu Setup Helper** menu will appear.

### 3) How to use the "Kawaiintu Setup Helper" menu

The interactive menu provides various setup choices. 
**Crucial First Step:** You must execute the **"base setting (Do first!)"** before applying any themes.
This will open the `gnome-shell-extension-manager` window. Please follow the instructions displayed by the helper:
1. Search for "User Themes" in the "Browse" tab.
2. Click the "Add" button to install it.
3. Go to the "Installed" tab and activate the Extension by toggling the header button to "ON".
4. Turn on the button specifically for "User Themes".
5. Close the window.
*(Reason: This GUI manipulation ensures that the Gnome-Shell-Extension reacts correctly to GNOME version updates.)*

#### Applying Themes and GDM (Login Screen)
The menu choices for color themes will set up both the Window Theme and the Shell Theme automatically.
During the installation, you can also customize the GDM login screen:
* Type `Y` when asked to change the login screen.
* You can drag-and-drop any image file (PNG, JPG, etc.) from your file manager directly into the terminal. The script will automatically convert and apply it by compiling the `.gresource` in the background!
* If you just press the Return key, you will be offered a choice to use the theme's default cute illustration or generate a solid dark background.

If you want to revert your system, you can choose the **"remove Kawaiintu/Moe-theme"** option to safely delete all custom themes and restore the default Ubuntu (Yaru) settings.

#### Applying Icons, Plymouth, and Wallpapers
* **Icons:** You can easily set or remove the Kawaii Icon packs.
* **Plymouth (Boot Screen):** Setup the adorable spinner screen when the OS loads. You can drag-and-drop a custom image or use the default cute example. You can also revert to the default Ubuntu spinner.
* **Wallpapers:** Easily change your desktop background. Drag and drop any image, and the helper will automatically handle format conversions and apply it to both light and dark modes.

#### Application Configurations
Kawaiintu Setup Helper also includes smart scripts to seamlessly manage system applications:
* **Firefox:** Switch between the Snap version and the Deb version (Deb version is recommended for full Kawaiintu theme compatibility).
* **File Managers:** Options to install, set up, or completely remove **Nemo** and **Thunar** (with pre-configured custom actions like "Open in Terminal").
* **Media Players:** Quickly remove default players like VLC if they are not needed.

#### Sounds
You can apply various Kawaii system sound themes (e.g., amateur voice actor versions, Maid versions, SF versions, or Hatsune Miku style). You can also easily remove all custom sounds to revert to the default system audio.

## 3. Known Errors
* In some instances on VirtualBox environments, the user-theme extension might fail to activate immediately. If this happens, apply the theme via "GNOME Tweaks" or simply reboot the virtual machine.
* If you upgrade your Ubuntu version without a clean install, the initial base setup might fail. In such cases, run `sudo apt remove gnome-shell-extension-manager`, reinstall it, and try the base setup again.

## 4. About forking and improving this Helper
This wrapper script is basically MIT licensed, so feel free to fork it, adapt it, or create local language versions.
**Note:** The core themes, Plymouth assets, and original Icons were originally created by Toy, with modifications and automated compilation systems integrated for Kawaiintu by Mifjpn. 
If you fork this setup helper, please ensure your script dynamically downloads the visual assets from GitHub, rather than including the theme files directly in your script repositories.
