<p align="center">
  <img src="images/icon.png" width="128" alt="4DJ">
</p>

<h1 align="center">4DJ</h1>

<p align="center">
  DJ software for macOS, Windows, Linux, iPhone and iPad (Android coming)<br>
  <b>English</b> · <a href="README.it.md">Italiano</a> · <a href="https://github.com/kikoz85/4dj/releases/latest"><b>Download</b></a>
</p>

<p align="center">
  <a href="https://github.com/kikoz85/4dj/releases/latest"><img src="https://img.shields.io/github/v/release/kikoz85/4dj?label=download&color=D4A64A" alt="Download"></a>
  <a href="https://apps.apple.com/app/4dj/id6830381237"><img src="https://img.shields.io/badge/App%20Store-Mac%2C%20iPhone%20%26%20iPad-0D96F6?logo=apple&logoColor=white" alt="Download on the App Store"></a>
  <a href="https://snapcraft.io/4dj-mixer"><img src="https://img.shields.io/badge/Snap%20Store-Linux-E95420?logo=snapcraft&logoColor=white" alt="Get it from the Snap Store"></a>
  <a href="https://apps.microsoft.com/detail/9P5BWS6LM4BB"><img src="https://img.shields.io/badge/Microsoft%20Store-get%20it-0078D4?logo=microsoft&logoColor=white" alt="Get it from the Microsoft Store"></a>
  <a href="https://www.enricofanucchi.com/en/app/4dj?utm_source=github&utm_campaign=4dj"><img src="https://img.shields.io/badge/website-enricofanucchi.com-F7941D" alt="Website"></a>
  <a href="https://github.com/sponsors/kikoz85"><img src="https://img.shields.io/badge/Sponsor-%E2%9D%A4-db61a2?logo=githubsponsors&logoColor=white" alt="Sponsor 4DJ on GitHub"></a>
</p>

![4DJ: two decks in sync, the mixer, FX units and the browser](images/main.png)

![The same in the Day look](images/main-day.png)

4DJ has the layout DJs already know: decks, mixer, effects and browser where you expect them, so you can start mixing right away. And it goes further: stems made on your own computer, transitions that stay in key and in tempo, a tablet as a second screen, and controllers that map themselves.

## Contents

- [Download and install](#download-and-install)
- [System requirements](#system-requirements)
- [What 4DJ does](#what-4dj-does)
- [Screenshots](#screenshots)
- [Kontrol S2 MK3](#kontrol-s2-mk3)
- [Keyboard](#keyboard)
- [Updates](#updates)
- [Support 4DJ](#support-4dj)
- [Questions](#questions)

## Download and install

Download the installer for your system from the [latest release](https://github.com/kikoz85/4dj/releases/latest).

| System | File | Install |
|---|---|---|
| macOS 13.4 or later (Apple Silicon and Intel) | [Mac App Store](https://apps.apple.com/app/4dj/id6830381237) | Install **4DJ** from the Mac App Store: free, and the App Store keeps it up to date. |
| macOS 13.4 or later (Apple Silicon and Intel) | `4DJ-<version>-macOS.dmg` | Open the DMG and drag 4DJ to Applications. The app is signed and notarized by Apple: it opens like any other. |
| iPhone and iPad, iOS/iPadOS 16 or later | [App Store](https://apps.apple.com/app/4dj/id6830381237) | Install **4DJ** from the App Store: free, and the App Store keeps it up to date. |
| Windows 10/11, x64 or ARM64 | [Microsoft Store](https://apps.microsoft.com/detail/9P5BWS6LM4BB) | Install **4DJ - DJ Mixer** from the Store: no warnings, and the Store keeps it up to date. |
| Windows 10/11, x64 or ARM64 | `4DJ-<version>-windows-x64.msi` or `-arm64.msi` | Run the MSI. If SmartScreen stops it, choose **More info → Run anyway**. |
| Linux x64 or ARM64, any distribution with snapd | [Snap Store](https://snapcraft.io/4dj-mixer) | Install **4DJ** from the Snap Store, or `sudo snap install 4dj-mixer`; the Snap Store keeps it up to date. For sound cards, MIDI and consoles: `sudo snap connect 4dj-mixer:alsa` and `sudo snap connect 4dj-mixer:raw-usb`. |
| Linux x64 or ARM64: Debian, Ubuntu, Mint… | `4dj_<version>_amd64.deb` or `_arm64.deb` | Open it with your software installer, or `sudo apt install ./4dj_<version>_amd64.deb` (`_arm64.deb` on ARM). |
| Linux x64 or ARM64: Fedora, openSUSE… | `4dj-<version>-1.x86_64.rpm` or `.aarch64.rpm` | Open it with your software installer, or `sudo dnf install ./4dj-<version>-1.x86_64.rpm` (`.aarch64.rpm` on ARM). |
| Linux x64 or ARM64: any distribution | `4DJ-<version>-linux-x86_64.AppImage` or `-aarch64.AppImage` | Make it executable (Properties → Allow executing) and open it. |

On first start the **Setup Assistant** asks for three things: the sound card, your music folders and how many decks you want. Coming from another DJ app? **Import collection…** in the browser (rekordbox, Serato, VirtualDJ or collection.nml) brings in your tracks with their BPM, keys, beatgrids, hotcues, ratings and playlists. The files are only read, never changed.

## System requirements

| | Minimum | Recommended |
|---|---|---|
| **macOS** | macOS 13.4, Intel or Apple Silicon, 8 GB RAM | Apple Silicon (M1 or later), 16 GB RAM |
| **Windows** | Windows 10 64-bit (x64 or ARM64), dual-core CPU, 8 GB RAM | Windows 11, quad-core CPU (Intel Core i5 8th gen / Ryzen 5 or better), 16 GB RAM |
| **Linux** | 64-bit (x64 or ARM64) with glibc 2.35: Ubuntu 22.04, Debian 12, Fedora 36 or later; GTK 3, PipeWire or ALSA; quad-core CPU, 8 GB RAM | Ubuntu 24.04, Debian 13, Fedora 39 or later (needed for StemX); PipeWire; 16 GB RAM |
| **iPhone / iPad** | iOS or iPadOS 16 | iPad with M1 or later |

For every system:

- **Disk:** about 1 GB for 4DJ and the StemX model, plus about 13 MB for each minute of music you separate into stems. An SSD loads tracks faster.
- **Sound:** any sound card works. To hear the next track in headphones you need a card with 4 outputs or a DJ controller with its own sound card (such as the Kontrol S2 MK3).
- **Screen:** 1280 × 800 or larger.
- **StemX** runs on the processor and is the heaviest task: on a low-power PC (such as an Intel N95) a track takes a few minutes; you can prepare stems in advance from the browser.

## What 4DJ does

### Decks
- 2 or 4 decks. Play, CUE (hold to preview, like a CDJ), 8 hotcues per track, loops from 1/2 to 32 beats, beatjump, Slip mode and reverse.
- Tempo fader with key lock, a KEY knob for ±12 semitones, and SYNC (Beat Sync or Tempo Sync).
- Scratch and nudge by dragging the waveform. Colour waveforms with zoom, overview, cue and loop markers, and a warning before the end of the track.
- A **phase meter** over each waveform shows how far the beats are from the other deck's: mixing by hand, keep the bar in the middle (it turns green when they are in time).

### StemX: stems on your computer
- Splits any track into **drums, bass, other and vocals**, without sending anything online.
- Select tracks in the browser and choose **Prepare Stems**. Each track is done once; while a deck plays, the work waits, so your set never slows down.
- On the deck, each stem has a volume, a mute, a filter and its own FX switch. **ACAP** keeps only the vocals, **INST** removes them.

### SmartSync and Key Morphing
- **SMART SYNC** makes the next crossfade harmonic and in tempo: the keys and tempos glide together and the new track ends up in its own key and tempo.
- **SMART** in the browser sorts the tracks by how well they mix with the one playing.

### Mixer and effects
- A club-style three-band EQ and filter. Crossfader with curve, auto crossfade, headphone cue mix.
- **Second device**: the master (or the headphones) can play on another sound device at the same time, e.g. the master on a Bluetooth speaker while the headphones stay on the console (Settings → Audio → Output Routing).
- Two FX units with 19 effects (delays, reverbs, flanger, phaser, gater, beatmasher and more), Insert or Post Fader.
- Mixer FX: the filter knob can be an effect. A **Maximizer** makes the master louder without clipping.

### Library and browser
- Track Collection, playlists, History, music folders and an **Explorer** for every folder and drive of your computer.
- Instant search, sorting, ratings, multiple selection, keys in Camelot, Open Key or musical notation, coloured by how they mix.
- **Smart Playlists** fill themselves from rules: BPM 124–128, Key 8A or the keys that mix with it, 4 stars or more, genre, added in the last 30 days, never played… with a live count while you edit.
- **Import collection…** brings your collection from **rekordbox** (XML export: File > Export Collection in xml format; rekordbox's own database is encrypted), **Serato** (the `_Serato_` folders in Music and on drives: crates, plus hotcues, loops and beatgrids from the files), **VirtualDJ** (database.xml and its playlists) and **collection.nml** files. Files are only read; tracks already in 4DJ are updated, not duplicated; playlists go in a folder named after the app.
- Your audio files are never modified.

### Safe sets
- **After an unexpected close** (a crash, a power cut) the decks come back with the same tracks, at the same place, with their loops, tempo and key lock, paused: press PLAY when you are ready.
- **Check Tracks…** on a playlist or the whole collection finds, before the gig, the tracks that are missing, cannot be read or are not analyzed, and fixes them: find moved files, analyze now, remove from the playlist.
- **Moved files are found again**: a track moved to another folder, or a drive that comes back with another letter or name, is found by itself (also when you load it on a deck); cues, beatgrid, rating and playlists stay with it.

### Recording, microphone and loops
- **Audio Recorder** with gain, level meter and CUT, to 24-bit WAV. Records the master or an external input.
- **Microphone** with talkover (the music goes down while you talk) and an **Aux** input.
- **Loop Recorder**: record 4 to 32 beats of the master, the cue, the microphone or aux, then overdub, undo and redo.

### Inputs, timecode and sync
- **Live Input** decks: a turntable or a CDJ through a deck's EQ, filter, FX and fader.
- **Timecode**: control vinyl or CDs (2 kHz or 1 kHz carrier) move the track (relative mode).
- **MIDI clock** out to drum machines and other gear, or in to follow them.

### Consoles and tablet
- The **Kontrol S2 MK3** works natively: see below. The **Kontrol S2 MK1, S2 MK2, S3, S4 MK2 and S4 MK3** work natively too, in Beta: a two-minute check in **Settings → Consoles** confirms every control and light on your console, and corrects what differs.
- **More than 110 MIDI consoles** are recognised as soon as they are plugged in and work at once, controls and lights. Each one is in Beta until you check it: a two-minute check in **Settings → Consoles** confirms every control and light and corrects what differs; then it is no longer Beta.
  - **Pioneer DJ**: DDJ-200, DDJ-400, DDJ-800, DDJ-1000, DDJ-FLX2, DDJ-FLX4, DDJ-FLX6, DDJ-FLX10, DDJ-GRV6, DDJ-REV1, DDJ-REV5, DDJ-REV7, DDJ-RB, DDJ-RR, DDJ-RZ, DDJ-RZX, DDJ-SB, DDJ-SB2, DDJ-SB3, DDJ-SX, DDJ-SX3, DDJ-SZ
  - **Hercules**: DJControl Inpulse 200, 300 and 500, Starlight, Compact, MIX, Jogvision, Instinct, AIR, MP3, MP3 e2 / MP3 LE / Glow, Steel; DJ Console RMX, RMX2, Mk2, Mk4, 4-Mx
  - **Numark**: Mixtrack, Mixtrack Pro, Mixtrack (Pro) II, Mixtrack (Pro) 3, Mixtrack Platinum, Mixtrack Platinum FX, Mixtrack Pro FX, Party Mix, DJ2Go, DJ2GO2 Touch, NS4FX, NS6II, NS7, N4, Mixstream Pro, Omni Control, Total Control, iDJ Live II
  - **Denon DJ**: MC3000, MC4000, MC6000MK2, MC7000
  - **Reloop**: Mixage, Beatmix 2/4 MK2, Terminal Mix 2/4, Beatpad, Jockey 3 Master Edition, Digital Jockey 2
  - **Behringer**: CMD STUDIO 4a, CMD Micro, CMD MM-1, BCD2000, BCD3000
  - **Vestax**: VCI-100, VCI-100MKII, VCI-300, VCI-400, Typhoon, Spin
  - **Korg**: KAOSS DJ, nanoKONTROL2, nanoPAD2 · **Novation**: Launchpad MK2, Launchpad Mini MK3 · **Akai**: LPD8 · **Allen & Heath**: Xone:K2 · **DJ TechTools**: MIDI Fighter Twister, MIDI Fighter Spectra
  - **Others**: Roland DJ-505, Stanton DJC.4, ION Discover DJ and Discover DJ Pro, MixVibes U-Mix Control 2 and Pro 2, Gemini FirstMix, DJ-Tech i-Mix Reload, DJ-Tech DJM-101 and Mixer One, Kontrol DJ KDJ500, M-Audio X-Session Pro, Evolution X-Session, Faderfox DJ2, M-Vave SMC-Mixer
- **CD and media players** work too, one deck each: the first one plugged in is deck A, the next deck B (Pioneer DJ CDJ-350, CDJ-850 and CDJ-2000, Denon DJ DN-SC2000 and DN-HS5500, Gemini CDMP-7000, American Audio Radius 2000, DJ-Tech CDJ-101).
- The **Kontrol Z1** mixer and the **Kontrol F1** work natively too (macOS, Windows, Linux, Android), in Beta.
- **Any other console** is set up with a guided assistant: a drawing shows the control to touch, you touch it on the console; the right deck is found from the left one, then the lights. Nothing to type.
- **Import Mapping (.tsi)**: a console mapping made in another DJ app works in 4DJ, controls and lights.
- **Test Console** records what a console sends and saves a report you can share if something does not work. Fine-tuning by hand stays in **Advanced Mapping**.
- **RemoteDeck**: a tablet or phone on the same network becomes a second screen and a touch surface (waveforms, hotcues, loops, XY pad for effects).

### Look and settings
- **Day and Night**: two looks, switched with the sun and the moon at the top right. Night is black and gold for dark booths, Day is light for daylight and outdoor sets.
- On a laptop the top bar shows the **battery**, so you always know how much is left during a set without mains power.
- Knobs show their value in percent while they move.
- A loading screen shows the version and each part of 4DJ as it loads.
- **iPhone and iPad**: on the iPad 4DJ has the full layout of the computer, on the iPhone a layout made for the phone. The Kontrol S2 MK3 works in its MIDI mode (hold the left FLX button while you plug it in).
- **Android** (coming): phone and tablet layouts for a whole set from the device, with the Kontrol S2 MK3 over USB.
- **Five languages**: English, Italiano, Français, Deutsch and Español. 4DJ starts in your system's language (English when it is another one) and you can change it in **Settings → Interface → Global**. The words DJs use everywhere (PLAY, CUE, SYNC, LOOP, FX…) stay the same in every language.
- **Help** inside 4DJ (the **?** at the top right): every function explained, with search, in your language.
- **A broken file never stops your set**: a damaged or non-audio file is refused, the deck flashes red with **CANNOT LOAD** and the file's name, and the music goes on.
- Complete settings, with **Export / Import** of all settings and **Reset to Defaults**.

## Screenshots

| | |
|---|---|
| ![Stems on deck B](images/stems.png) | ![Loop Recorder and Audio Recorder](images/recorders.png) |
| **StemX**: deck B as drums, bass, other and vocals. | **Loop Recorder** and **Audio Recorder** in the FX slots, switched with their tabs. |
| ![Mixer FX](images/settings-mixer-fx.png) | ![Effects](images/settings-effects.png) |
| **Mixer FX**: the effects of the S2 MK3's FX SELECT buttons. | **Effects**: routing and the effects offered in the menus. |
| ![Consoles](images/settings-consoles.png) | ![Console setup](images/console-setup.png) |
| **Consoles**: what is plugged in and whether it is ready, mapping import, test. | **Console setup**: touch the control the drawing shows. |
| ![Input Routing](images/settings-input-routing.png) | ![Timecode](images/settings-timecode.png) |
| **Input Routing**: microphone and aux with live meters, talkover. | **Timecode**: each deck plays its track, a timecode record or its input. |
| ![Mix Recorder](images/settings-mix-recorder.png) | ![Analysis](images/settings-analysis.png) |
| **Mix Recorder**: source, folder, file name, split size. | **Analysis**: BPM range, automatic cue, key notation, stems folder. |
| ![Updates](images/settings-updates.png) | |
| **Updates**: automatic check and Check for Updates. | |

## Kontrol S2 MK3

Plug it in and 4DJ uses it at once, sound card included (master and headphones), on macOS, Windows and Linux. 4DJ starts where the console is set: faders, EQ, gain, filter, crossfader and volume are read from it when it connects, so a low fader or a full bass knob left on the console is the same on screen. When 4DJ closes, the console's lights go off. On Windows and Linux 4DJ takes its sound card in low-latency mode: about 7 ms on Windows, about 8 ms on Linux (16 ms where the system does not give audio real-time priority, so that it never drops out).

On Linux the .deb and .rpm also give 4DJ access to the console when they install: nothing else to do. With the AppImage, the first time you plug the console in 4DJ asks to enable it: choose **Enable** and type your password once. With the Snap, connect `alsa` and `raw-usb` once (see Download and install); for consoles driven over HID, such as the S2 MK3, 4DJ shows the command to type when you plug it in.

| Control | In 4DJ |
|---|---|
| PLAY, CUE, SYNC, KEYLOCK | As printed on the console (SHIFT + CUE: back to the start; SHIFT + SYNC: master; SHIFT + KEYLOCK: tempo range) |
| FLX, REV | Slip mode; reverse while held |
| Jog wheel | Top: scratch. Side: nudge. SHIFT: fast search |
| Pads | HOTCUES, SHIFT + HOTCUES = loops, SAMPLES = Sample Deck, SHIFT + SAMPLES = stems |
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

4DJ looks for a new release at every start and every few hours; when there is one, **UPDATE** shows at the top until you install it. In **Settings → Interface → Updates** you can switch this off, or use **Check for Updates** at any time. **Download and Install** downloads the installer for your system and opens it; nothing is installed without you. If you installed 4DJ from the Microsoft Store, the App Store or the Snap Store, the store updates it instead.

## Support 4DJ

4DJ is free and built in spare time. If it helps you, you can support its development with **[GitHub Sponsors](https://github.com/sponsors/kikoz85)** (the **Sponsor** button is also at the top of this page and in the app, under **Settings → Interface → Global** and **About**) or from the [Support](https://www.enricofanucchi.com/en/support?utm_source=github&utm_campaign=4dj) page of the website. Donations paid for the signed macOS app and will pay for a signed Windows installer, so Windows too stops asking for confirmation on first launch, and for the time to build the next versions. A ⭐ on the repository helps too.

## Questions

**Where are my settings?** In 4DJ. **Settings → Export…** saves them to a file, for a backup or another computer; **Import…** brings them back.

**Does 4DJ change my music files?** No. BPM, keys, grids, cues and ratings stay in 4DJ's library.

**On Windows, why do other apps go silent on the console's sound card?** For the lowest latency 4DJ takes the Kontrol S2 MK3's card for itself (exclusive mode). Other apps play again when 4DJ closes; in **Settings → Audio → Devices** you can switch exclusive mode off (higher latency).

**Where are my recordings?** In Music/4DJ Recordings, or the folder chosen in **Settings → Recording → Mix Recorder**.

**Can I bring my collection from another DJ app?** Yes: **Import collection…** in the browser reads rekordbox (XML export), Serato, VirtualDJ and collection.nml files, with BPM, keys, beatgrids, hotcues, ratings and playlists. The files are only read, never changed.

---

Copyright © 2026 Enrico Fanucchi. All rights reserved. Third-party components: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

Kontrol S2 MK3 is a product of Native Instruments GmbH; other names are trademarks of their owners. 4DJ is independent software, not affiliated with or endorsed by them.
