# API Tweaks — NetLimiter AutoPatcher

Automated patcher for NetLimiter. No PowerShell, no hex editing, no manual DLL swapping — just run it and you're done.

[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Qn2MEEW3NN)
[![Downloads](https://img.shields.io/badge/%23downloads-Channel-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/channels/1082095781466607637/1338764503428497441)
[![VladF4](https://img.shields.io/badge/@VladF4-Profile-9966CC?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/430983824504258561)

---

## Features

- Fully automated as it stops the services, backs up files, injects DLLs, restarts, and handles dekstop shortcuts
- Drag & drop your NetLimiter exe or folder onto the app to skip folder selection
- Auto-detects your NetLimiter install if it's in the default location
- Creates a desktop shortcut and removes the old NetLimiter one
- Lofi background music with crossfade between tracks
- Single self-contained exe, no install required

---

## Requirements

- Windows 10 or 11 (x64)
- NetLimiter 5 installed

---

## How to use

**Standard:**
1. Download `API Tweaks.exe` from [Releases](../../releases/latest)
2. Run it
3. Select your NetLimiter folder if it wasn't auto-detected
4. Click Patch Now

**Drag & drop:**
1. Drag your `NLClientApp.exe` or NetLimiter folder onto `API Tweaks.exe`
2. Click through while folder detection is pre-filled

> **SmartScreen will warn you** on first run since the exe isn't signed. Click **More info → Run anyway**.

---

## FAQ

**It says NLClientApp.exe wasn't found:**
Try selecting the actual NetLimiter install folder / .exe, not a shortcut. Default location is `C:\Program Files\Locktime Software\NetLimiter`.

**The service won't stop:**
Run the app as administrator.

**NetLimiter updated and it stopped working:**
Grab the latest release. I rebuild with updated DLLs whenever NetLimiter pushes an update.

**Antivirus is flagging it:**
Expected. The exe modifies system files and injects DLLs so it looks suspicious to AV. It's clean, dm and ill show the source if you don't trust.

---

## Updates

Whenever NetLimiter releases an update I'll rebuild with the new DLLs and push a new release. Just download the latest exe and run it again.

---

<sub>Built by @VladF4</sub>
