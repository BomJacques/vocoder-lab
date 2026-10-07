# vocoder-lab
VOCODER LAB effect and instrument VST3 builds for Windows x64.

## Download

**[Download VOCODER LAB 0.5.1 — effect and instrument VST3 ZIP](https://github.com/BomJacques/vocoder-lab/raw/refs/heads/main/downloads/VOCODER-LAB-0.5.1-VST3-win64.zip)**

The ZIP is visible in [`downloads`](downloads) and on the [0.5.1 release page](https://github.com/BomJacques/vocoder-lab/releases/tag/v0.5.1), with its SHA-256 checksum. Previous 0.4.0 and 0.5.0 downloads and releases remain available.

## Install

1. Extract the ZIP.
2. Copy the complete `VOCODER LAB.vst3` and/or `VOCODER LAB INSTRUMENT.vst3` folders from `Binaries/Release` to your DAW's VST3 scan location.
3. Rescan or restart the DAW. Use the instrument for keyboard-playable speech; use the effect for audio processing.

Windows x64, VST3 only. No standalone app. Requires the Microsoft Visual C++ x64 runtime. Keep each entire `.vst3` folder together.

## Build contents

Ten speech choices: Formant, TI keyboard/chip pitch, SP0256, SC-01A, MEA8000, FOF, Digitalker, FS-inspired 8+8 and Klatt. LPC-10 is a separate mono output codec with approximately 166 ms intentional delay. SID/Amstrad AY carriers, offline typed speech, singing controls, grouped phonetic assignments and 38 presets are included. FS and Klatt have dedicated Engine character panels.

Version 0.5.1 fixes clicks on note runs across all speech engines: connected-note timing is preserved and active retriggers use a short 3 ms output transition. Fast TI staccato retains core continuity. The earlier FS sine-table assertion fix and stable legacy automation mapping remain included. Debug and Release each pass 13/13 automated tests; the packaged effect and instrument pass extracted VST3 loading/processing and checksum checks. Usage, tested scope and attribution are included in the ZIP.

Development build: actual Reason sessions and subjective voice fidelity remain unverified. Speech data is authored. FS-inspired is an architectural interpretation, not an FS1R firmware/patch/FSeq emulator; Klatt is a reference-backed synthesis port, not DECtalk/Perfect Paul. Complete original hardware or a percentage of sound equivalence is not claimed.
