
# Fluent (Dark) Theme for OBS Studio

<p align="center">
  <img src="images/WinUI%203%20Logo.png" width="300" style="border-radius: 8px;" alt="WinUI 3 Logo">
</p>

A clean, modern, and dark-mode Fluent Design theme for OBS Studio, updated and rebuilt to be compatible with OBS Studio v28+ (including Qt6 support). This theme brings a Windows 11 / WinUI 3-inspired design style to your streaming setup with crisp custom icons, modern padding, and vibrant blue focus highlights.

---

## <img src="images/install.svg" width="24" height="24" valign="middle" /> Installation Instructions

To ensure OBS Studio can find and load all modern theme assets correctly, please follow these steps:

### Step 1: Prepare the Files
1. Download the files from this repository.
2. Ensure you have the following folder structure:
   - `fluentdark.obt` (Theme configuration file)
   - `fluentdark.qss` (Styles and layouts)
   - `fluentdark/` (Folder containing custom `.svg` assets and icons)

> [!WARNING]  
> <img src="images/warning.svg" width="18" height="18" valign="middle" /> **Important Folder Name Rule**  
> The assets folder **must** be named exactly `fluentdark` (all lowercase, no spaces). This ensures that OBS Studio's internal resource resolver (`theme:fluentdark/...`) can map the icons correctly.

### Step 2: Move to the OBS Themes Directory
Copy `fluentdark.obt`, `fluentdark.qss`, and the `fluentdark` folder into your operating system's custom OBS themes directory:

* **Windows:**
  Press `Win + R`, paste `%appdata%\obs-studio\themes` and hit `Enter`. Move the files there.

  *(Alternatively: `C:\Program Files\obs-studio\data\obs-studio\themes\`)*

* **macOS:**
  `~/Library/Application Support/obs-studio/themes/`

* **Linux (Flatpak):**
  `~/.var/app/com.obsproject.Studio/config/obs-studio/themes/`

* **Linux (Standard):**
  `~/.config/obs-studio/themes/`

### Step 3: Enable the Theme in OBS
1. Launch OBS Studio.
2. Go to **Settings** > **General** > **Theme**.
3. Select **Fluent (Dark)** from the dropdown menu.
4. Click **Apply** and then **OK**.

---

## <img src="images/signature.svg" width="24" height="24" valign="middle" /> Credits

### Theme Authors
* **Walker** (Maintainer, Repository Owner, and Curator)
* **dogeshep** (Original theme concept & design assets)
* **pigney** (Aesthetic framework / Grey-tint adaptations)
* **Philippe Groarke** (Original OBS theme code contributor / GNU General Public License holder)

### AI Contributor
* **Gemini** (Google's AI Assistant)
  * Rebuilt the classic Fluent stylesheet layout, translating raw assets into OBS 28+'s unified `@OBSThemeVars` system and resolving Qt6 cross-platform resource path conflicts.

### Design References
* **Microsoft Windows App Development (WinUI 3):** This theme incorporates layout structures, spacing, and accent principles modeled after Microsoft's official developer visual documentation. All design concepts remain copyrighted to Microsoft.

---

## <img src="images/license.svg" width="24" height="24" valign="middle" /> License

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 2 of the License, or (at your option) any later version. See the `LICENSE` file for more details.
