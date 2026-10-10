# Game Agent — downloads

This page holds the installers of **Game Agent**, a Windows app for recording gameplay.

## Install

1. Open **[Releases](../../releases/latest)** and download `GameAgent_<version>_x64-setup.exe`.
2. Run it. Windows may say *"Windows protected your PC"* because the beta is not code-signed yet:
   choose **More info → Run anyway**.
3. Start **Game Agent** from the Start menu.

Requirements: Windows 10 or 11, 64-bit. No account, no other software.

## Updates

The app checks this page for a newer version and offers it inside the app. Every update is verified with the
app's own signature before it is installed, and it is never installed while you are recording.

## Your recordings

Recordings stay on your PC, in `%LOCALAPPDATA%\GameAgent\recordings`. Nothing is uploaded.

## Third-party software

The installer includes [FFmpeg](https://ffmpeg.org) (LGPL v3 build by BtbN, unmodified; source:
https://github.com/FFmpeg/FFmpeg, build scripts: https://github.com/BtbN/FFmpeg-Builds).
