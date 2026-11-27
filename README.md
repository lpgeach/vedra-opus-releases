[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H4S12B9OKI)
# Vedra Opus

Vedra Opus is a desktop app for building interactive eLearning courses: slides, layers and triggers, quizzes, audio and video, and publishing to SCORM, xAPI, cmi5 or plain HTML.

This repository is where its test builds are published, so you can download and try them. The source code is at **[lpgeach/vedra-opus-source](https://github.com/lpgeach/vedra-opus-source)**, under the GNU General Public License, version 3 or later.

[![Sponsor Vedra Opus](https://img.shields.io/badge/Sponsor-Vedra%20Opus-db61a2?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/lpgeach)

<img src="images/editor-light.png" alt="The Vedra Opus editor in its light theme, with the demo course open on its title slide: slides on the left, the slide on the stage, its triggers on the right and its timeline below" width="920">

<img src="images/editor-dark.png" alt="The editor in its dark theme, showing the demo course's slide of four statistics about the UK space industry" width="920">

_The editor in its light and dark themes, with the demo course, The UK Space Industry in 2026._

## ⬇️ Download

**Latest: [Vedra Opus 0.1.0 alpha 5](https://github.com/lpgeach/vedra-opus-releases/releases/tag/v0.1.0-alpha.5)** for Windows, macOS and Linux.

### Windows 10 or 11 (64-bit)

1. Download **[`Vedra-Opus-0.1.0-alpha.5-x64.exe`](https://github.com/lpgeach/vedra-opus-releases/releases/download/v0.1.0-alpha.5/Vedra-Opus-0.1.0-alpha.5-x64.exe)** (238 MB).
2. Run it. The alpha is **not signed** yet, so Windows shows "Windows protected your PC": choose **More info → Run anyway**.
3. Choose where to install it, and start Vedra Opus from the Start menu.

### macOS 11 or later

1. Download the one for your Mac:
   - **Apple Silicon** (M1 and later): **[`Vedra-Opus-0.1.0-alpha.5-arm64.dmg`](https://github.com/lpgeach/vedra-opus-releases/releases/download/v0.1.0-alpha.5/Vedra-Opus-0.1.0-alpha.5-arm64.dmg)** (275 MB)
   - **Intel**: **[`Vedra-Opus-0.1.0-alpha.5-x64.dmg`](https://github.com/lpgeach/vedra-opus-releases/releases/download/v0.1.0-alpha.5/Vedra-Opus-0.1.0-alpha.5-x64.dmg)** (292 MB)
   - Not sure? Apple menu → About This Mac: "Chip: Apple M…" is Apple Silicon; "Processor: Intel" is Intel.
2. Open it and drag **Vedra Opus** into **Applications**.
3. The alpha is **not notarised by Apple** yet, so the first time macOS will not open it. Try opening it once, then go to **System Settings → Privacy & Security** and choose **Open Anyway** beside Vedra Opus.

### Linux (64-bit)

Choose one:

- **AppImage**, for most distributions: download **[`Vedra-Opus-0.1.0-alpha.5-x86_64.AppImage`](https://github.com/lpgeach/vedra-opus-releases/releases/download/v0.1.0-alpha.5/Vedra-Opus-0.1.0-alpha.5-x86_64.AppImage)** (288 MB), make it executable (`chmod +x Vedra-Opus-0.1.0-alpha.5-x86_64.AppImage`) and run it. If it does not start, install FUSE 2 (on Ubuntu 24.04: `sudo apt install libfuse2t64`).
- **Debian or Ubuntu package:** download **[`Vedra-Opus-0.1.0-alpha.5-amd64.deb`](https://github.com/lpgeach/vedra-opus-releases/releases/download/v0.1.0-alpha.5/Vedra-Opus-0.1.0-alpha.5-amd64.deb)** (231 MB), then `sudo apt install ./Vedra-Opus-0.1.0-alpha.5-amd64.deb`.

For text-to-speech on Linux, install espeak-ng (`sudo apt install espeak-ng`). The Linux version is built and tested on a current Ubuntu; much older distributions may not run it.

### Checking a download

Their SHA-256:

```
49a2a8acf7b1f7e5a1a24522ff4950d0d3622c8459141a82c47c9dffb7187a3d  Vedra-Opus-0.1.0-alpha.5-x64.exe
269b30870e5d30688b68acae9d6218e2d4e01142c8234e9e9ace4bdfa22bf52e  Vedra-Opus-0.1.0-alpha.5-arm64.dmg
d2776f644e1c3f32c5a6f2d5609cdb3368c73bcc272fee6c0155ee49b24433f0  Vedra-Opus-0.1.0-alpha.5-x64.dmg
dac1b2248cf9c030da829a771962fadc6b0fe0740317fa514eedb09e2f2398bc  Vedra-Opus-0.1.0-alpha.5-x86_64.AppImage
1235bfddcb1a6519ae59ba8e868e9c4234e35b3cc1123bfac4cee3fc26f77f22  Vedra-Opus-0.1.0-alpha.5-amd64.deb
```

In PowerShell: `Get-FileHash .\Vedra-Opus-0.1.0-alpha.5-x64.exe`. In the macOS Terminal: `shasum -a 256 Vedra-Opus-0.1.0-alpha.5-arm64.dmg`. On Linux: `sha256sum Vedra-Opus-0.1.0-alpha.5-x86_64.AppImage`.

## 🚀 Getting started

- On the Welcome screen, **Explore the Demo Course** opens a finished sample course to look through, preview and change.
- **New Project** starts a blank course; **New from Template…** starts from one of the starter templates.
- **Import PowerPoint…** and **Import Storyline Course…** bring in existing material.

## ⚠️ This is an alpha

- Things will be missing and some will break. Keep copies of projects you care about.
- **Projects saved in alpha 5 cannot be opened in alpha 4 or earlier,** because they use a newer project format.
- **Updates:** **Help → Check for Updates** finds new versions here on Windows (from alpha 4) and in the Linux AppImage (from alpha 5). On macOS, with the .deb, and from alpha 3 or earlier, download new versions from this repository's [Releases](https://github.com/lpgeach/vedra-opus-releases/releases) page.

## 📦 Third-party source

Vedra Opus ships ffmpeg (LGPL 2.1 or later) and LibreOffice (MPL 2.0). The complete source of both, exactly as built for each version, is published here alongside it: for alpha 5, **[Third-party source for Vedra Opus 0.1.0 alpha 5](https://github.com/lpgeach/vedra-opus-releases/releases/tag/sources-0.1.0-alpha.5)**. You do not need it to install or use the app.

**Help → Third-Party Notices…** in the app lists every licence, including the demo course's music and pictures.

## 💜 Support Vedra Opus

If Vedra Opus is useful to you, you can support its development through GitHub Sponsors:

[![Sponsor Vedra Opus](https://img.shields.io/badge/Sponsor-Vedra%20Opus-db61a2?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/lpgeach)
