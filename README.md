<p align="center">
  <img src="assets/banner.jpg" width="960" alt="Ink Player" />
</p>

<p align="center">
  <a href="https://github.com/Svekolsky/InkPlayer-Releases/releases/download/v0.7/InkPlayer-Setup-0.7.exe"><img src="assets/download.svg" width="256" height="56" alt="Download for Windows — Installer, 64-bit, 3.2 MB" /></a>
  &nbsp;
  <a href="https://github.com/Svekolsky/InkPlayer-Releases/releases/download/v0.7/InkPlayer-0.7.zip"><img src="assets/zip.svg" width="232" height="56" alt="ZIP — EXE and install script, 1.1 MB" /></a>
</p>

<p align="center">
  Windows 10 / 11, 64-bit &nbsp;·&nbsp; Free &nbsp;·&nbsp; VLC installed automatically if missing &nbsp;·&nbsp; <a href="https://github.com/Svekolsky/InkPlayer-Releases/releases">All releases</a>
</p>

<br />

A quiet, dark video player for Windows on the VLC engine.

<img src="assets/screenshot.png" width="960" alt="Ink Player window with a splash screen, seek bar, subtitle and audio track buttons" />

## Features

- **Resume** — position, audio and subtitle tracks are remembered per file.
- **Seamless loop** — clips up to 2 minutes repeat without a pause; one button turns it off.
- **Create subtitles** (Ctrl+T) — local speech recognition with whisper.cpp, translated into Russian.
- **Tracks at a glance** — Subtitles and Audio buttons show what's playing; add SRT / ASS / SSA / VTT / SUB.
- **Full-resolution frames** — Shift+S saves a PNG at the video's original size, even when paused.
- **Calm fullscreen** — the control bar and cursor slide away after 3 seconds.
- **Russian or English** — switch any time in *About*.

<details>
<summary>Keys</summary>

Space play / pause · ← → ±10 s (Shift: 1 min) · ↑ ↓ volume · M mute · F fullscreen · Shift+S save frame · Ctrl+O open · Ctrl+T subtitles · Ctrl+− / Ctrl++ / Ctrl+0 subtitle size

</details>

## Install

**Installer** — per-user, no admin rights; adds *Open with* for 24 formats and installs VLC if it is missing.  
**ZIP** — `InkPlayer.exe` plus a PowerShell install script (install VLC from videolan.org yourself).

## Privacy

Playback, recognition and frame capture run locally. Ink goes online only when you ask: to download the subtitle model, translate subtitles or check for updates. The installer downloads VLC from videolan.org only if it is missing. No ads, no telemetry. Checksums: **SHA256SUMS.txt** in each release.

## Author

Svekolsky — [Telegram](https://t.me/Svekolsky)
