[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H4S12B9OKI)
# Vedra Opus

Vedra Opus is a desktop app for building interactive eLearning courses: slides, layers and triggers, quizzes, audio and video, and publishing to SCORM, xAPI, cmi5 or plain HTML.

This repository is where its test builds are published, so you can download and try them. The source code is at **[lpgeach/vedra-opus-source](https://github.com/lpgeach/vedra-opus-source)**, under the GNU General Public License, version 3 or later.

[![Sponsor Vedra Opus](https://img.shields.io/badge/Sponsor-Vedra%20Opus-db61a2?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/lpgeach)

<img src="images/editor-light.png" alt="The Vedra Opus editor in its light theme, with the demo course open on its title slide: slides on the left, the slide on the stage, its triggers on the right and its timeline below" width="920">

<img src="images/editor-dark.png" alt="The editor in its dark theme, showing the demo course's slide of four statistics about the UK space industry" width="920">

_The editor in its light and dark themes, with the demo course, The UK Space Industry in 2026._

## ⬇️ Download

**Latest: [Vedra Opus 0.1.0 alpha 4](https://github.com/lpgeach/vedra-opus-releases/releases/tag/v0.1.0-alpha.4)** for Windows and macOS.

### Windows 10 or 11 (64-bit)

1. Download **[`Vedra-Opus-0.1.0-alpha.4-x64.exe`](https://github.com/lpgeach/vedra-opus-releases/releases/download/v0.1.0-alpha.4/Vedra-Opus-0.1.0-alpha.4-x64.exe)** (238 MB).
2. Run it. The alpha is **not signed** yet, so Windows shows "Windows protected your PC": choose **More info → Run anyway**.
3. Choose where to install it, and start Vedra Opus from the Start menu.

### macOS 11 or later

1. Download the one for your Mac:
   - **Apple Silicon** (M1 and later): **[`Vedra-Opus-0.1.0-alpha.4-arm64.dmg`](https://github.com/lpgeach/vedra-opus-releases/releases/download/v0.1.0-alpha.4/Vedra-Opus-0.1.0-alpha.4-arm64.dmg)** (276 MB)
   - **Intel**: **[`Vedra-Opus-0.1.0-alpha.4-x64.dmg`](https://github.com/lpgeach/vedra-opus-releases/releases/download/v0.1.0-alpha.4/Vedra-Opus-0.1.0-alpha.4-x64.dmg)** (292 MB)
   - Not sure? Apple menu → About This Mac: "Chip: Apple M…" is Apple Silicon; "Processor: Intel" is Intel.
2. Open it and drag **Vedra Opus** into **Applications**.
3. The alpha is **not notarised by Apple** yet, so the first time macOS will not open it. Try opening it once, then go to **System Settings → Privacy & Security** and choose **Open Anyway** beside Vedra Opus.

The Apple Silicon version is new and has not yet been tried on an Apple Silicon Mac; the Intel version also runs on those Macs, through Rosetta.

### Checking a download

Their SHA-256:

```
f28ce0203032efdc9b61cd4076dfb0ad6f31f64eeb099eb6bf2e5221bc7e0488  Vedra-Opus-0.1.0-alpha.4-x64.exe
12e995edd7ba74dc11cd9640f4f034f92578c896c9a128b2c8fbef4de8f7a2de  Vedra-Opus-0.1.0-alpha.4-arm64.dmg
7e63136318191b8f7419e42c4bc371309444beb7d1070571c30e42768dc11091  Vedra-Opus-0.1.0-alpha.4-x64.dmg
```

In PowerShell: `Get-FileHash .\Vedra-Opus-0.1.0-alpha.4-x64.exe`. In the macOS Terminal: `shasum -a 256 Vedra-Opus-0.1.0-alpha.4-arm64.dmg`.

There are no Linux installers yet.

## 🚀 Getting started

- On the Welcome screen, **Explore the Demo Course** opens a finished sample course to look through, preview and change.
- **New Project** starts a blank course; **New from Template…** starts from one of the starter templates.
- **Import PowerPoint…** and **Import Storyline Course…** bring in existing material.

## ⚠️ This is an alpha

- Things will be missing and some will break. Keep copies of projects you care about.
- **Updates:** from alpha 4, **Help → Check for Updates** on Windows finds new versions here. On macOS, and from alpha 3 or earlier, download new versions from this repository's [Releases](https://github.com/lpgeach/vedra-opus-releases/releases) page.

## 📦 Third-party source

Vedra Opus ships ffmpeg (LGPL 2.1 or later) and LibreOffice (MPL 2.0). The complete source of both, exactly as built for each version, is published here alongside it: for alpha 4, **[Third-party source for Vedra Opus 0.1.0 alpha 4](https://github.com/lpgeach/vedra-opus-releases/releases/tag/sources-0.1.0-alpha.4)**. You do not need it to install or use the app.

**Help → Third-Party Notices…** in the app lists every licence, including the demo course's music and pictures.

## 💜 Support Vedra Opus

If Vedra Opus is useful to you, you can support its development through GitHub Sponsors:

[![Sponsor Vedra Opus](https://img.shields.io/badge/Sponsor-Vedra%20Opus-db61a2?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/lpgeach)
