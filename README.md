<p align="center"><img src="kdm-logo.png" width="96" alt="KDM logo"></p>

# KDM

A download manager for Windows. KDM speeds up downloads, picks up the files your browser starts, and downloads videos from web pages.

**[⬇️ Download KDM for Windows](https://github.com/bakersendev/kdm-releases/releases/download/v0.1.0/KDM_0.1.0_x64-setup.exe)** (version 0.1.0)

Older versions: [all releases](https://github.com/bakersendev/kdm-releases/releases). Only the `.exe` is needed; GitHub adds "Source code" links to every release, which hold only this page's text.

This page only hosts the installers. KDM is in early testing (pre-release).

## Install

1. Download `KDM_<version>_x64-setup.exe` from the [releases page](https://github.com/bakersendev/kdm-releases/releases).
2. Open it. If Windows shows a blue warning, click **More info**, then **Run anyway**.
   This warning is normal for a new app that is not yet signed with Microsoft.
3. Click **Next** until it finishes.

To update, install the new version over the old one. Your downloads and settings are kept.

## Add KDM to your browser (Edge or Chrome)

1. In KDM, open **Settings** and turn on **Browser integration**.
2. Go to `edge://extensions` (Chrome: `chrome://extensions`) and turn on **Developer mode**.
3. Click **Load unpacked** and choose KDM's extension folder. KDM's **How to use** page shows the folder and has a button to open it.
4. Click the KDM icon in the browser and choose **Allow on all sites**.

Developer mode is only needed because KDM is not in the browser stores yet. The extension only talks to KDM on your computer.

## Check the download (optional)

Each release lists the file's SHA-256. In PowerShell:

```powershell
Get-FileHash .\KDM_0.1.0_x64-setup.exe
```

The result should match the one on the release page.
