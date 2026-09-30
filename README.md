<p align="center"><img src="docs/logo.png" width="140" alt="Akshara"></p>

<h1 align="center">Akshara</h1>
<p align="center">Kinetic captions for every script.<br>
Word-accurate animated captions in 99 languages, text behind the subject, and GPU export, all on your own computer.</p>

<p align="center"><a href="https://github.com/cxaiiii/akshara-releases/releases"><b>Download the alpha</b> (Windows · macOS)</a> · <a href="https://chaii.wtf">chaii.wtf</a></p>

> **Alpha.** Akshara is in early testing. This repository hosts the downloads and the issue
> tracker; the source is private.

## What it does

- **Word-level transcription in 99 languages**, on your GPU (NVIDIA, AMD, Intel or Apple
  Silicon) with a CPU fallback. Devanagari, Bengali, Tamil, Arabic, Thai, Japanese, Korean and more
  render natively, not as boxes.
- **18 caption styles** — Hormozi, Beast, Karaoke, Typewriter, Bounce, Neon, Glitch, Cinematic,
  One Word and more. Beat Pulse and Voice Pulse move with the music and the speaker's voice.
- **Text behind the subject.** One click separates the person from the background, so titles sit
  behind them.
- **Export** an MP4 with captions burned in (hardware encoding), or a transparent overlay
  (ProRes 4444 / VP9) for Premiere Pro, After Effects or DaVinci Resolve. Subtitles export to SRT,
  VTT and ASS.
- **Private by default.** Transcription and subject separation run locally and nothing is
  uploaded. Optional cloud extras (Groq transcription, AI emphasis, emoji and translation) use
  your own Groq key and only run when you pick them.

## Requirements

- **Windows 10 or 11**, 64-bit
- **macOS 12 or later** on Apple Silicon (M1 or newer)
- About 1.5 GB of free space: the app, plus speech and subject models downloaded on first use.
  A GPU is recommended, not required.

## Installing an alpha build

Alpha builds are not notarised by Apple or signed with a certificate Windows trusts yet, so
both systems ask before the first launch.

- **Windows:** if SmartScreen says "Windows protected your PC", click **More info → Run anyway**.
  The installer is signed by "Chaii" with a self-signed certificate.
- **macOS:** drag Akshara to Applications and open it once. On macOS 15 Sequoia or later, go to
  **System Settings → Privacy & Security** and click **Open Anyway**. On macOS 12–14, right-click
  the app → **Open**. Or in Terminal: `xattr -dr com.apple.quarantine /Applications/Akshara.app`

Exports from the free alpha carry a small "Made with Akshara" mark. Alpha testers can ask for a
key (**Settings → Licence**) that removes it.

## Reporting bugs

[Open an issue](https://github.com/cxaiiii/akshara-releases/issues) and attach the log file:
`%APPDATA%\Akshara\akshara.log` on Windows, `~/Library/Application Support/Akshara/akshara.log`
on macOS.

## Third-party software

Akshara uses FFmpeg (LGPL), whisper.cpp, ONNX Runtime, open speech and segmentation models, and
open-licensed fonts. See [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

---

Made by Chaii · https://chaii.wtf
