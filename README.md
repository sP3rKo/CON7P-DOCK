<div align="center">

# C0N7P Dock
### Smart Floating Command Center for Windows 11

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078D6?style=for-the-badge&logo=windows)](https://github.com/sP3rKo/CON7P-DOCK/releases/latest)
[![Version](https://img.shields.io/badge/Version-1.0.0-6366F1?style=for-the-badge)](https://github.com/sP3rKo/CON7P-DOCK/releases/latest)
[![Built With](https://img.shields.io/badge/Built%20With-Electron%20%26%20JS-10B981?style=for-the-badge&logo=electron)](https://www.electronjs.org/)

**C0N7P Dock** is a lightweight, glassmorphic floating capsule tucked neatly at the top edge of your Windows 11 screen. Designed for speed without clutter, it stays hidden until you hover over the top bezel or press `Alt + Space`.

[Download Installer (v1.0.0)](https://github.com/sP3rKo/CON7P-DOCK/releases/download/v1.0.0/C0N7P.Dock.Setup.1.0.0.exe) • [All Releases](https://github.com/sP3rKo/CON7P-DOCK/releases) • [Developer Instagram (@c0n7p)](https://instagram.com/c0n7p)

</div>

---

## ✨ Key Features

- **Smart Top-Edge Peek Mode:** Tucks neatly into the top bezel of your screen without blocking active windows or cluttering the taskbar. Auto-collapses when clicking outside or pressing `Esc`.
- **30-Day Upcoming Task Hub:** Automatically organizes tasks from today up to 30 days ahead (*Today*, *Tomorrow*, and upcoming dates) with a live task counter pill.
- **Real-Time Media, Volume & Brightness Sync:** Detects active browser/system media playback and provides instant two-way synchronization with Windows 11 volume and screen brightness.
- **Color-Coded Live Countdown & Stopwatch:** Set custom timers (minutes & seconds) that remain visible at the top of your screen, shifting to yellow and red with a triple alarm chime upon completion.
- **Instant Keyboard Layout Fixer (`ع ⇄ EN`):** Typed a whole sentence on the wrong keyboard layout? One click converts between Arabic and English layouts and copies the fixed text straight to your clipboard.
- **Keep Screen Awake (Caffeine Mode):** Prevents Windows from sleeping or locking during large downloads or presentations with a live top-edge status indicator.
- **Custom Glow Themes:** Switch between *Classic Dark*, *Cyber Indigo*, *RGB Neon*, and *Battery Adaptive* glow borders.
- **Bilingual Interface (English / العربية):** Auto-detects system locale with instant `LTR` / `RTL` switching via the built-in settings gear ⚙️.
- **Custom Quick Shortcuts & Clipboard History:** Launch favorite URLs or local folders, jot down notes in the persistent scratchpad, and access your last 5 copied items.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Alt` + `Space` | Toggle / Expand **C0N7P Dock** from any application |
| `Esc` | Collapse Dock back to the top edge |
| `Enter` | Quickly add a task to the selected date |

---

## 🚀 Installation (For Users)

1. Download **`C0N7P.Dock.Setup.1.0.0.exe`** directly from **[Here](https://github.com/sP3rKo/CON7P-DOCK/releases/download/v1.0.0/C0N7P.Dock.Setup.1.0.0.exe)** or visit the **[Releases Page](https://github.com/sP3rKo/CON7P-DOCK/releases/latest)**.
2. Run the installer. *(If Windows SmartScreen appears on first launch, click **More info** → **Run anyway**).*
3. Once installed, **C0N7P Dock** will appear in your Start Menu and launch automatically with Windows.

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
