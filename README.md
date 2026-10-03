<p align="center"><img src="docs/logo.png" width="140" alt="Akshara"></p>

<h1 align="center">Akshara</h1>
<p align="center">Kinetic captions for every script.<br>
Animated, word-accurate captions in 99 languages, dubbing, text behind you, and 3D titles that live in your scene.</p>

<p align="center"><a href="https://github.com/cxaiiii/akshara-releases/releases/latest"><b>Download the alpha</b> (Android · Windows · macOS)</a> · <a href="https://akshara.chaii.wtf">Open in your browser</a> · <a href="https://chaii.wtf/akshara">chaii.wtf/akshara</a></p>

> **Alpha, invite-only.** Akshara is in early testing. [Request an invite](https://akshara.chaii.wtf/?apply),
> then sign in with the same account in the browser, on Android, Windows and Mac. This repository
> hosts the downloads and the issue tracker; the source is private.

## What it does

- **Captions in 99 languages, timed to every word.** Devanagari, Bengali, Tamil, Arabic, Thai,
  Japanese, Korean and more render properly, not as boxes, and Hinglish stays in one script.
- **18 caption styles:** Hormozi, Beast, Karaoke, Typewriter, Bounce, Neon, Glitch, Cinematic,
  One Word and more. Beat Pulse and Voice Pulse move with the music and the speaker's voice.
  Every style can be restyled and reanimated word by word.
- **Dubbing.** Your video in Hindi, Tamil, Bengali, Telugu, Marathi, Gujarati, Kannada, Malayalam
  and more, in a natural voice or your own, with your music kept underneath and new captions to
  match.
- **Sound design.** Whooshes, pops and hits placed on your words and beats.
- **Cut out anything.** Tap a person or any object to cut it out through the whole video; titles,
  captions and effects can then sit behind it.
- **A real timeline:** zoom, trim, split, merge, group, keyframes, text layers, fixed caption boxes.
- **3D (Windows and Mac).** Camera tracking keeps 3D titles fixed in your scene; lighting and
  colour are matched to your footage, with shadows on the floor. A 3D workspace adds shapes,
  imported models (glTF, OBJ, FBX), materials, modifiers and particles: particles can pour out
  of your captions or bounce off a cut-out person. Floors, walls and tables in the shot are
  found for you to stand text on.
- **Cinematic renders (Windows and Mac).** Blender's Cycles path tracer is built in, for
  realistic light on 3D titles.
- **Export** an MP4 ready for Reels, Shorts or TikTok. The desktop app also exports a transparent
  overlay (ProRes 4444 / VP9) for Premiere Pro, After Effects or DaVinci Resolve. Subtitles
  export to SRT, VTT and ASS.

## Platforms

| | Android | Browser | Windows | macOS |
|---|---|---|---|---|
| Captions, styles, animation, text | ✓ | ✓ | ✓ | ✓ |
| Cut-outs, dubbing, sound design | ✓ | ✓ | ✓ | ✓ |
| 3D, camera tracking, cinematic renders | | | ✓ | ✓ |
| Overlay export for editing apps | | | ✓ | ✓ |

The 3D tools, dubbing and sound design come to Windows and Mac with the alpha.15 desktop
installers, which are being added to the [alpha.15 release](https://github.com/cxaiiii/akshara-releases/releases/tag/v0.1.0-alpha.15).

- **Android 7 or newer.** Keep Android System WebView up to date (it updates from the Play Store).
- **Browser:** Chrome or Edge on a computer; Chrome on Android phones.
- **Windows 10 or 11**, 64-bit. **macOS 12 or later** on Apple Silicon (M1 or newer).
- Desktop: about 1.5 GB of free space for the app and the speech and cut-out models it downloads
  on first use. A GPU helps, but isn't required.

## Installing an alpha build

None of the builds are store-signed yet, so each system asks before the first launch.

- **Android:** open the APK on your phone. If it asks, allow installing apps from that source
  (Chrome, Files or WhatsApp), then tap **Install**. If Play Protect says it doesn't know the app,
  tap **More details → Install anyway**. Finished videos are saved to your gallery under
  **Movies › Akshara**.
- **Windows:** if SmartScreen says "Windows protected your PC", click **More info → Run anyway**.
  The installer is signed by "Chaii" with a self-signed certificate.
- **macOS:** drag Akshara to Applications and open it once. On macOS 15 Sequoia or later, go to
  **System Settings → Privacy & Security** and click **Open Anyway**. On macOS 12–14, right-click
  the app → **Open**. Or in Terminal: `xattr -dr com.apple.quarantine /Applications/Akshara.app`

Early-access exports carry a small "Made with Akshara" mark.

## Privacy

Your video stays on your device on every platform. The desktop app writes captions on your own
computer; in the browser and on Android only the sound is sent, to write the captions. Dubbing
sends the voice and the words to our dubbing service.

## Reporting bugs

[Open an issue](https://github.com/cxaiiii/akshara-releases/issues) with your device and what you
did. On desktop, attach the log file: `%APPDATA%\Akshara\akshara.log` on Windows,
`~/Library/Application Support/Akshara/akshara.log` on macOS.

## Third-party software

Akshara uses FFmpeg (LGPL), whisper.cpp, ONNX Runtime, MediaPipe, three.js, Blender's Cycles
(Apache-2.0), Capacitor, open speech and segmentation models, and open-licensed fonts. See
[THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

---

Made by [Chaii](https://chaii.wtf)
