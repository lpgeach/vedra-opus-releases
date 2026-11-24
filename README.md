# Vedra Opus

Vedra Opus is a desktop app for building interactive eLearning courses: slides, layers and triggers, quizzes, audio and video, and publishing to SCORM, xAPI, cmi5 or plain HTML.

This repository is where its test builds are published, so you can download and try them. The app's own code is not here.

## ⬇️ Download

**Latest: [Vedra Opus 0.1.0 alpha 3](https://github.com/lpgeach/vedra-opus-releases/releases/tag/v0.1.0-alpha.3)** for Windows 10 or 11 (64-bit).

1. Download **[`Vedra-Opus-0.1.0-alpha.3-x64.exe`](https://github.com/lpgeach/vedra-opus-releases/releases/download/v0.1.0-alpha.3/Vedra-Opus-0.1.0-alpha.3-x64.exe)** (238 MB).
2. Run it. The alpha is **not signed** yet, so Windows shows "Windows protected your PC": choose **More info → Run anyway**.
3. Choose where to install it, and start Vedra Opus from the Start menu.

To check the download, its SHA-256 is:

```
363949c40cf580088b06b304a0b220beae3795f616de0daccbcd60db5c9f1526
```

In PowerShell: `Get-FileHash .\Vedra-Opus-0.1.0-alpha.3-x64.exe`.

There are no macOS or Linux installers yet.

## 🚀 Getting started

- On the Welcome screen, **Explore the Demo Course** opens a finished sample course to look through, preview and change.
- **New Project** starts a blank course; **New from Template…** starts from one of the starter templates.
- **Import PowerPoint…** and **Import Storyline Course…** bring in existing material.

## ⚠️ This is an alpha

- Things will be missing and some will break. Keep copies of projects you care about.
- **Help → Check for Updates** does not work in alpha 3. New versions appear on this repository's [Releases](https://github.com/lpgeach/vedra-opus-releases/releases) page.

## 📦 Third-party source

Vedra Opus ships ffmpeg (LGPL 2.1 or later) and LibreOffice (MPL 2.0). The complete source of both, exactly as built for each version, is published here alongside it: for alpha 3, **[Third-party source for Vedra Opus 0.1.0 alpha 3](https://github.com/lpgeach/vedra-opus-releases/releases/tag/sources-0.1.0-alpha.3)**. You do not need it to install or use the app.

**Help → Third-Party Notices…** in the app lists every licence, including the demo course's music and pictures.
