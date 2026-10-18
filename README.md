# Exam Mistake Tracker

A study app for keeping practice exams, question screenshots, mistakes and review together.

**[Download for Windows or Mac](https://github.com/sebmansfield/exam-mistake-tracker-downloads/releases/latest)** · **[Open in browser after installing](https://sebmansfield.github.io/exam-mistake-tracker-downloads/)**

## Install on Windows

1. Download **Exam-Mistake-Tracker-V10-Setup.exe** from the latest release.
2. Run setup. It downloads and verifies the full Windows desktop app, then opens the installation wizard.
3. You can select **Browser shortcut on desktop** during setup. The Windows Start menu always includes **Open in browser**.

Requires 64-bit Windows 10 or 11. Internet is needed for the initial download. The installed study tools work offline.

## Install on Mac

From the same [download page](https://github.com/sebmansfield/exam-mistake-tracker-downloads/releases/latest), choose **macOS Apple Silicon** for an M-series Mac or **macOS Intel** for an Intel Mac. Open the DMG, drag **Exam Mistake Tracker** into **Applications**, and open it once from Applications.

Requires **macOS 13 or later**. Python is bundled. The Mac version includes V10.0.3's older question label fix and uses the same study tools, local records, screenshots, backups and browser view as the Windows app.

This is an early Mac testing build, ad-hoc signed and not yet notarized by Apple. macOS may block its first launch. Keep Gatekeeper enabled; use [Apple's individual-app guidance](https://support.apple.com/en-au/102445) only if you trust the download.

## Open the full browser version

Use the [browser launcher page](https://sebmansfield.github.io/exam-mistake-tracker-downloads/) and click **Open in browser**. It starts a local session without opening the desktop window. Your browser may ask you to confirm opening the installed tracker.

For direct access, drag **Open in browser** from that page to your bookmarks bar. The launcher link is `exam-mistake-tracker://browser`; it can also be pasted into a browser that supports installed application links. You can bookmark the launcher page itself instead. Bookmarking the temporary localhost address alone cannot start a stopped program.

The desktop dashboard also has **Open in browser**. Desktop and browser share the same local records, images and study tools. You can close the desktop window while the browser stays open. The local session stops shortly after all tracker views close. Nothing starts automatically with Windows or macOS.

Records stay on this computer. There is no cloud storage, phone access or automatic sync to another computer. Each person has their own records. Export backups to keep a separate copy.

## Update an existing V10 installation

Export a backup, then choose **Settings → Updates → Import app update** and select a newer compatible `.emtupdate` file. The current Mac download already includes V10.0.3; the older V10.0.2 update is for earlier Windows installations. This keeps the installation’s existing profile. Open the updated desktop app once to register its browser launcher.

On Windows, running a fresh installer creates an empty profile and preserves previous profiles; import your backup to transfer records into the new installation.

This repository contains downloads, the browser launcher page, instructions and Mac packaging/verification support. The Mac workflow reconstructs the app from its existing release files; the public build configuration is not a separate installer. The original application source archive and private update-signing key are not published here.
