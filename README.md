# WWM Music Studio: downloads

WWM Music Studio is a Windows app that plays songs on the instrument in **Where Winds Meet** for you. Load a MIDI, MusicXML or text song, or convert your own piano recording or a video link, then press **F8** in game and the app presses the keys.

This repository only holds the downloads. Each new version is published here automatically, and the installed app checks here for updates.

## Download and install

1. Open the [latest build](https://github.com/Jupacker/WWM_MusicStudio-Releases/releases/tag/latest-build).
2. Under **Assets**, download **WWM-Music-Studio-Setup.exe**.
3. Double-click it. It installs and opens the app, and there's nothing else to install.

If you'd rather not install anything, download **WWM-Music-Studio-Portable.exe** instead and run it directly.

**"Windows protected your PC"?** The app isn't code-signed, so Windows SmartScreen may warn you the first time. Click **More info**, then **Run anyway**.

## Updates

The installed app updates itself. It downloads each new version in the background and installs it the next time you restart the app. To install it straight away, click **Restart to update** at the top of the window, or go to *Settings → App updates*.

The portable version can't replace itself. It tells you when a new version is out, and you download it again from this page.

## What it does

- **Plays in game:** press **F8** to start or stop, **F7** to pause, and **F9** to skip. You can change these hotkeys in *Settings*.
- **Converts recordings:** turns a piano recording, phone video or video link (YouTube and others) into a playable song. It also makes sheet music and a falling-notes video. The first conversion downloads the converter once, which is about 1 GB.
- **Song Check:** finds the spots that won't play cleanly on the game's 36 keys, and **Fix for WWM** rewrites them.
- **Practice:** slows a section down and loops it while you learn it.
- **Mini player:** a small window that stays on top of the game.
- **Human feel:** adds tiny timing differences so playback sounds less mechanical.

## Files on each release

| File | What it is |
| --- | --- |
| `WWM-Music-Studio-Setup.exe` | The installer. Most people want this one. |
| `WWM-Music-Studio-Portable.exe` | Runs without installing, but doesn't update itself. |
| `latest.yml`, `*.blockmap` | Used by the app's updater. You don't need to download these. |

Only convert and play music you have the right to use.
