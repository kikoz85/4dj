<p align="center">
  <img src="images/icon.png" width="128" alt="4DJ">
</p>

<h1 align="center">4DJ</h1>

<p align="center">
  DJ software for macOS, Windows, Linux and Android<br>
  <b>English</b> · <a href="README.it.md">Italiano</a> · <a href="https://github.com/kikoz85/4dj/releases/latest"><b>Download</b></a>
</p>

![4DJ: two decks in sync, the mixer, FX units and the browser](images/main.png)

4DJ is laid out like Traktor Pro, so if you know Traktor you can start mixing right away. It adds what Traktor does not have: stems made on your own computer, transitions that stay in key and in tempo, a tablet as a second screen, and controllers that map themselves.

## Contents

- [Download and install](#download-and-install)
- [What 4DJ does](#what-4dj-does)
- [Screenshots](#screenshots)
- [Traktor Kontrol S2 MK3](#traktor-kontrol-s2-mk3)
- [Keyboard](#keyboard)
- [Updates](#updates)
- [Questions](#questions)

## Download and install

Download the installer for your system from the [latest release](https://github.com/kikoz85/4dj/releases/latest).

| System | File | Install |
|---|---|---|
| macOS 13.4 or later (Apple Silicon and Intel) | `4DJ-<version>-macOS.dmg` | Open the DMG and drag 4DJ to Applications. The first time, macOS may say it cannot check the app: open **System Settings → Privacy & Security** and choose **Open Anyway**. |
| Windows 10/11, x64 or ARM64 | `4DJ-<version>-windows-x64.msi` or `-arm64.msi` | Run the MSI. If SmartScreen stops it, choose **More info → Run anyway**. |
| Linux, x64 or ARM64 (Debian, Ubuntu…) | `4dj_<version>_amd64.deb` or `_arm64.deb` | `sudo apt install ./4dj_<version>_amd64.deb`, then start 4DJ from the menu. |
| Android 10 or later, tablets and phones | `4DJ-<version>-android.apk` | Open the APK on the device and allow installing from that source. |

On first start the **Setup Assistant** asks for three things: the sound card, your music folders and how many decks you want. Coming from Traktor? **Import Traktor collection** in the browser brings in your tracks with their BPM, keys, beatgrids, hotcues, ratings and playlists. Traktor's own files are only read, never changed.

## What 4DJ does

### Decks
- 2 or 4 decks, as in Traktor. Play, CUE (hold to preview, like a CDJ), 8 hotcues per track, loops from 1/2 to 32 beats, beatjump, Flux mode and reverse.
- Tempo fader with key lock, a KEY knob for ±12 semitones, and SYNC (Beat Sync or Tempo Sync).
- Scratch and nudge by dragging the waveform. Colour waveforms with zoom, overview, cue and loop markers, and a warning before the end of the track.

### StemX: stems on your computer
- Splits any track into **drums, bass, other and vocals**, without sending anything online.
- Select tracks in the browser and choose **Prepare Stems**. Each track is done once; while a deck plays, the work waits, so your set never slows down.
- On the deck, each stem has a volume, a mute, a filter and its own FX switch. **ACAP** keeps only the vocals, **INST** removes them.

### SmartSync and Key Morphing
- **SMART SYNC** makes the next crossfade harmonic and in tempo: the keys and tempos glide together and the new track ends up in its own key and tempo.
- **SMART** in the browser sorts the tracks by how well they mix with the one playing.

### Mixer and effects
- EQ and filter that sound like Traktor's, measured from it. Crossfader with curve, auto crossfade, headphone cue mix.
- Two FX units with 19 effects (delays, reverbs, flanger, phaser, gater, beatmasher and more), Insert or Post Fader.
- Mixer FX: the filter knob can be an effect. A **Maximizer** makes the master louder without clipping.

### Library and browser
- Track Collection, playlists, History, music folders and an **Explorer** for every folder and drive of your computer.
- Instant search, sorting, ratings, multiple selection, keys in Camelot, Open Key or musical notation, coloured by how they mix.
- Your audio files are never modified.

### Recording, microphone and loops
- **Audio Recorder** with gain, level meter and CUT, to 24-bit WAV. Records the master or an external input.
- **Microphone** with talkover (the music goes down while you talk) and an **Aux** input.
- **Loop Recorder**: record 4 to 32 beats of the master, the cue, the microphone or aux, then overdub, undo and redo.

### Inputs, timecode and sync
- **Live Input** decks: a turntable or a CDJ through a deck's EQ, filter, FX and fader.
- **Timecode**: Traktor Scratch or Serato control vinyl moves the track (relative mode).
- **MIDI clock** out to drum machines and other gear, or in to follow them.

### Controllers and tablet
- **Traktor Kontrol S2 MK3** works natively: see below.
- MIDI controllers are mapped automatically when known; any other is mapped with MIDI learn, or by holding a button and touching the control on screen.
- **RemoteDeck**: a tablet or phone on the same network becomes a second screen and a touch surface (waveforms, hotcues, loops, XY pad for effects).

### Settings
- Every page of Traktor's preferences that 4DJ has a function for, with **Export / Import** of all settings and **Reset to Defaults**.

## Screenshots

| | |
|---|---|
| ![Stems on deck B](images/stems.png) | ![Loop Recorder and Audio Recorder](images/recorders.png) |
| **StemX**: deck B as drums, bass, other and vocals. | **Loop Recorder** and **Audio Recorder** in the FX slots, switched with their tabs. |
| ![Mixer FX](images/settings-mixer-fx.png) | ![Effects](images/settings-effects.png) |
| **Mixer FX**: the effects of the S2 MK3's FX SELECT buttons. | **Effects**: routing and the effects offered in the menus. |
| ![Input Routing](images/settings-input-routing.png) | ![Timecode](images/settings-timecode.png) |
| **Input Routing**: microphone and aux with live meters, talkover. | **Timecode**: each deck plays its track, a timecode record or its input. |
| ![Mix Recorder](images/settings-mix-recorder.png) | ![Analysis](images/settings-analysis.png) |
| **Mix Recorder**: source, folder, file name, split size. | **Analysis**: BPM range, automatic cue, key notation, stems folder. |
| ![Updates](images/settings-updates.png) | |
| **Updates**: automatic check and Check for Updates. | |

## Traktor Kontrol S2 MK3

Plug it in and 4DJ uses it at once, sound card included (master and headphones).

| Control | In 4DJ |
|---|---|
| PLAY, CUE, SYNC, KEYLOCK | As in Traktor (SHIFT + CUE: back to the start; SHIFT + SYNC: master; SHIFT + KEYLOCK: tempo range) |
| FLX, REV | Flux mode; reverse while held |
| Jog wheel | Top: scratch. Side: nudge. SHIFT: fast search |
| Pads | HOTCUES, SHIFT + HOTCUES = loops, SAMPLES = Remix Deck, SHIFT + SAMPLES = stems |
| BROWSE | Turn to choose, push to load |
| MOVE | Beatjump |
| LOOP | Turn: resize the active loop, or pick the size of the next. Push: loop on/off |
| FX SELECT 1–4 | FX 1: filter on/off. FX 2–4: the effect chosen in Settings → Mixer FX |
| MIC | Microphone on/off, with talkover |
| QUANT | Quantize |
| Mixer | Gain, EQ, filter, faders, crossfader, headphones, VU meters |

## Keyboard

| Keys (deck A / deck B) | Function |
|---|---|
| Q / P | CUE (hold to preview) |
| W / O | Play / pause |
| E / I | SYNC |
| 1 2 3 4 / 7 8 9 0 | Hotcues 1–4 |
| D / J | Loop on / off |
| ← → | Crossfader |
| ↑ ↓ | Previous / next track in the browser |
| Shift ← / Shift → | Load the selected track into deck A / B |
| ⌘F | Search |
| ⌘1 – ⌘4 | Layouts: Essential, Mixer, Extended, Browser |

On Windows and Linux, ⌘ is Ctrl. Press **?** in 4DJ for the full list.

## Updates

4DJ checks for a new release once a day at start and tells you when there is one. In **Settings → Interface → Updates** you can switch this off, or use **Check for Updates** at any time. **Download and Install** downloads the installer for your system and opens it; nothing is installed without you.

## Questions

**Where are my settings?** In 4DJ. **Settings → Export…** saves them to a file, for a backup or another computer; **Import…** brings them back.

**Does 4DJ change my music files?** No. BPM, keys, grids, cues and ratings stay in 4DJ's library.

**Where are my recordings?** In Music/4DJ Recordings, or the folder chosen in **Settings → Recording → Mix Recorder**.

**Can I use my Traktor collection?** Yes: **Import Traktor collection** in the browser. It reads it and changes nothing in Traktor.

---

Copyright © 2026 Enrico Fanucchi. All rights reserved. Third-party components: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
