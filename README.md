<div align="center">

# C0N7P Dock
### Ultra-Light Smart Command Center & Control Studio for Windows 11

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078D6?style=for-the-badge&logo=windows)](https://github.com/sP3rKo/CON7P-DOCK/releases/latest)
[![Version](https://img.shields.io/badge/Version-1.1.0-10B981?style=for-the-badge)](https://github.com/sP3rKo/CON7P-DOCK/releases/latest)
[![RAM Usage](https://img.shields.io/badge/RAM%20Usage-~50MB%20Ultra--Light-6366F1?style=for-the-badge)](https://github.com/sP3rKo/CON7P-DOCK)
[![Built With](https://img.shields.io/badge/Built%20With-Electron%20%26%20JS-F59E0B?style=for-the-badge&logo=electron)](https://www.electronjs.org/)

**C0N7P Dock** is an ultra-lightweight, glassmorphic floating capsule tucked neatly at the top edge of your Windows 11 screen, paired with a standalone **Control Studio** app for full customization. Engineered with an **Eco Memory Engine (~50MB RAM)** so it runs effortlessly even on low-spec laptops.

[Download Latest Installer (v1.1.0)](https://github.com/sP3rKo/CON7P-DOCK/releases/download/v1.1.0/C0N7P.Dock.Setup.1.1.0.exe) • [All Releases](https://github.com/sP3rKo/CON7P-DOCK/releases) • [Developer Instagram (@c0n7p)](https://instagram.com/c0n7p)

</div>

---

## ✨ What Makes C0N7P Dock Different?

- **⚡ Ultra-Light Eco Memory Engine (~50MB RAM):** Hardware acceleration disabled, memory-capped V8 runtime, and **Smart Idle Pause** (zero background polling when tucked away) — built to run smoothly on any PC.
- **🎛️ Standalone Control Studio App:** Open **C0N7P Dock** from the Start Menu or the gear icon (`⚙️`) to launch a dedicated customization window where you can pick any custom HEX glow color, toggle individual tabs/modules on or off, and enable Eco Mode.
- **📂 Quick File Shelf (Drag & Drop):** Drag any file or image into the Dock's shelf to hold it temporarily, then drag it out into any browser, chat, or folder whenever you need it.
- **🎨 Instant Screen Color Picker (EyeDropper):** Sample any pixel color anywhere on your screen with one click and automatically copy its `HEX` code.
- **🌧️ Built-in Focus Ambient Sound (0MB Audio):** Generate soothing brown/white focus noise natively via Web Audio API while running your countdown timer — without bulky audio files.
- **📅 30-Day Upcoming Task Hub:** Automatically organizes tasks across *Today*, *Tomorrow*, and the next 30 days with a live counter pill.
- **⌨️ Instant Keyboard Layout Fixer (`ع ⇄ EN`):** Fix sentences typed on the wrong Arabic/English keyboard layout and copy the corrected text in one click.
- **☕ Keep Screen Awake & Live System Sync:** Prevent Windows sleep, control live media playback, volume, and screen brightness, and receive seamless auto-updates via GitHub Releases.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Alt` + `Space` | Toggle / Expand **C0N7P Dock** from any application |
| `Esc` | Collapse Dock back to the top edge |
| `Enter` | Quickly add a task to the selected date |

---

## 🚀 Installation (For Users)

1. Download **`C0N7P.Dock.Setup.1.1.0.exe`** directly from **[Here](https://github.com/sP3rKo/CON7P-DOCK/releases/download/v1.1.0/C0N7P.Dock.Setup.1.1.0.exe)** or visit the **[Releases Page](https://github.com/sP3rKo/CON7P-DOCK/releases/latest)**.
2. Run the installer. *(If Windows SmartScreen appears on first launch, click **More info** → **Run anyway**).*
3. Launch **C0N7P Dock** from the Start Menu to open the **Control Studio** and customize your dock, while the floating capsule docks automatically at the top of your screen.

---

## 🛠️ Run From Source (For Developers)

```bash
# Clone the repository
git clone [https://github.com/sP3rKo/CON7P-DOCK.git](https://github.com/sP3rKo/CON7P-DOCK.git)

# Navigate to the project folder
cd CON7P-DOCK

# Install dependencies
npm install

# Run in development mode
npm start

# Build Windows installer (.exe)
npm run dist
