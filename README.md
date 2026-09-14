# Pixel Grabber

Screenshot, annotation, color picking and floating reference tools for graphic designers, by DesignByKazbo. Formerly TintShot.

**Recommended beta: [Pixel Grabber 0.4.0 Beta 8](https://github.com/KazboXIII/TintShot/releases/tag/v0.4.0-beta.8)**

- [Download the Windows x64 installer](https://github.com/KazboXIII/TintShot/releases/download/v0.4.0-beta.8/PixelGrabber-0.4.0-beta.8-Setup-x64.exe) — installation and built-in update support.
- [Download the portable Windows x64 ZIP](https://github.com/KazboXIII/TintShot/releases/download/v0.4.0-beta.8/PixelGrabber-0.4.0-beta.8-Portable-x64.zip) — extract and run TintShot.exe without installing.
- [Beta notes](https://github.com/KazboXIII/TintShot/releases/download/v0.4.0-beta.8/BETA-NOTES.txt), [tester guide](https://github.com/KazboXIII/TintShot/releases/download/v0.4.0-beta.8/TESTER-GUIDE.txt), and [SHA-256 checksums](https://github.com/KazboXIII/TintShot/releases/download/v0.4.0-beta.8/SHA256SUMS.txt).

Beta 8 introduces the Pixel Grabber name and a redesigned dark workspace: rounded panels, lavender accents, purple/teal lighting, an icon annotation toolbar, a new welcome screen and clearer settings navigation. The 175% fullscreen toolbar and dedicated Pen button from Beta 7 remain.

Requires Windows 10 version 1809 or newer / Windows 11, Intel or AMD x64, and .NET Framework 4.8. ARM Windows is not supported in this beta. The application and installer are unsigned.

- **Ctrl+Shift+2:** capture a region and annotate it on screen.
- **Ctrl+Shift+3:** pick a screen color.
- **Ctrl+Shift+1:** open the design desk.
- **Ctrl+,** or the tray menu: settings and customizable shortcuts.

Close the previous Pixel Grabber, TintShot or Surge Capture copy before installing. Upgrades preserve your local library, settings, startup preference and existing installation folder, and replace older TintShot shortcuts with Pixel Grabber shortcuts. **Beta 4/5 users should install Beta 8 manually once** because those older builds can fail to connect to GitHub.

Installed copies check GitHub Releases after launch and every six hours; you choose when to install. Downloads are checked against GitHub's SHA-256 asset digest. Settings > Updates controls automatic checks and beta releases; enable beta releases to receive Beta 8. Portable copies can check for updates but require manual replacement or installation.

The repository remains **KazboXIII/TintShot** so existing updaters keep working. The internal executable remains **TintShot.exe**, and data stays in `%LOCALAPPDATA%\SurgeCapture`. The TintShot-named release downloads are byte-identical compatibility aliases; new downloads should use the PixelGrabber names above.

There are no capture uploads or telemetry. Closing the main window hides the app in the tray by default; use the tray's Quit command to exit.

This repository distributes releases and product documentation. Older releases remain available. Read the release notes for tested coverage and the tester guide before reporting issues. Some retained historical sections in the bundled notes use older product names; Beta 8's visible app and shortcuts use Pixel Grabber.
