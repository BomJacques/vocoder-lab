# vocoder-lab
VOCODER LAB effect and instrument VST3 builds for Windows x64.

## Download

**[Download VOCODER LAB 0.6.0 — effect and instrument VST3 ZIP](https://github.com/BomJacques/vocoder-lab/raw/refs/heads/main/downloads/VOCODER-LAB-0.6.0-VST3-win64.zip)**

The ZIP and SHA-256 checksum are visible in [`downloads`](downloads) and on the [0.6.0 release page](https://github.com/BomJacques/vocoder-lab/releases/tag/v0.6.0). All previous downloads and releases remain available.

## Install

1. Extract the ZIP.
2. Copy the complete `VOCODER LAB.vst3` and/or `VOCODER LAB INSTRUMENT.vst3` folders from `Binaries/Release` to your DAW's VST3 scan location.
3. Rescan or restart the DAW. Use the instrument for keyboard-playable speech; use the effect for audio processing.

Windows x64, VST3 only. No standalone app. Requires the Microsoft Visual C++ x64 runtime. Keep each entire `.vst3` folder together.

## Phrase performance in 0.6

Choose **PHRASE / TI welcome** and play MIDI notes **48, 50, 52 and 53**. In **Phonic Keys → Phrase keys**, select a piano note, type words and press **Build & assign**. Edit each phoneme, duration and pitch offset; use One-shot, Hold or Loop, with optional host-tempo sync. One phrase plays at a time, with the latest mapped note taking over. Existing unmapped sound keys retain their polyphony. The phrase bank, steps and text drafts save with projects and presets; restoring never autoplays. There are four phrase presets and **42 presets total**.

Rounded phonetic tiles remain the default mapping view. Click a tile to replace the selected note's phrase with a single sound. The earlier note-run click fix is retained; user feedback confirms the clicks have stopped. The new phrase workflow still needs user testing in Reason.

## Build contents

Ten speech choices: Formant, TI keyboard/chip pitch, SP0256, SC-01A, MEA8000, FOF, Digitalker, FS-inspired 8+8 and Klatt. LPC-10 is a separate mono output codec with approximately 166 ms intentional delay. SID/Amstrad AY carriers, offline typed speech, singing controls, immediate phonetic assignments and MIDI capture/export are included. FS and Klatt have dedicated Engine character panels.

Debug and Release each pass **14/14** automated suites, including phrase timing/retriggers, sustain/channel ownership, state recall, UI assignment and callback allocation guards. Both packaged VST3s pass extracted load/process and checksum checks. Instructions, scope and attribution are included in the ZIP.

Speech data is authored. FS-inspired is an architectural interpretation, not an FS1R firmware/patch/FSeq emulator; Klatt is a reference-backed synthesis port, not DECtalk/Perfect Paul. Full original-hardware or percentage-fidelity equivalence is not claimed. Broader full-DAW and subjective voice-fidelity validation remain unverified.
