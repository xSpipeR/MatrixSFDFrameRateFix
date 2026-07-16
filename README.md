# Matrix SFD FrameRate Fix

Compatibility add-on for **SayNoToSync's Framerate Fix** for **The Matrix: Path of Neo**.
Tested throughout the entire game.

The original 60 FPS patch can cause SFD cutscenes to end prematurely due to timing issues. This compatibility fix restores the original 30 FPS timing during SFD video playback while preserving smooth 60 FPS gameplay, allowing the game to be completed without interrupted cutscenes.

---

## Features

- 60 FPS gameplay
- Automatic 30 FPS playback for SFD movies
- Prevents SFD cutscenes from ending prematurely
- Automatic return to 60 FPS gameplay after cutscenes
- F10 switch to original 30 FPS timing for problematic scripted sequences
- Workaround for the first-level elevator bug
- Source code included

---

## Requirements

- The Matrix: Path of Neo
- SayNoToSync's Framerate Fix
- Ultimate ASI Loader

---

## Installation

1. Install SayNoToSync's Framerate Fix.
2. Download the latest release from the **Releases** section.
3. Copy `zzz_MatrixSFDFrameRateFix.asi` into the game's installation directory.
4. Open `TheMatrixPathOfNeo.WidescreenFix.ini`.
5. Set:

```ini
FixFrameRate = 1
FrameRate = 60
```

6. Launch the game.

---

## Download

Download the latest release from the **Releases** section of this repository.

---

## Credits

**Compatibility Fix**

- SpipeR

**Original Framerate Fix**

- SayNoToSync

---

## License

Released under the MIT License.
