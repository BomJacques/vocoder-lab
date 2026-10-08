# vocoder-lab
VOCODER LAB effect and instrument VST3 builds for Windows x64.

## Download

**[Download VOCODER LAB 0.6.1 — effect and instrument VST3 ZIP](https://github.com/BomJacques/vocoder-lab/raw/refs/heads/main/downloads/VOCODER-LAB-0.6.1-VST3-win64.zip)**

The ZIP and SHA-256 checksum are visible in [`downloads`](downloads) and on the [0.6.1 release page](https://github.com/BomJacques/vocoder-lab/releases/tag/v0.6.1). All previous downloads and releases remain available.

## Install

1. Extract the ZIP.
2. Copy the complete `VOCODER LAB.vst3` and/or `VOCODER LAB INSTRUMENT.vst3` folders from `Binaries/Release` to your DAW's VST3 scan location.
3. Rescan or restart the DAW. Use the instrument for keyboard-playable speech; use the effect for audio processing.

Windows x64, VST3 only. No standalone app. Requires the Microsoft Visual C++ x64 runtime. Keep each entire `.vst3` folder together.

## Easier controls in 0.6.1

The GUI now starts in **Easy**. Use the header switch for **Advanced** routing and detailed editing. **Phonic Keys** has persistent **Sound tiles / Words to keys** navigation. Select a key on the upper piano, then click a tile or type words and press **Assign words**. The lower piano plays the saved assignments.

**Speech Synth → Vowel touch pad** opens the large draggable vowel surface in either view. Hold a note or enable Audition voice, drag to shape the sound, choose a target note and save the vowel. **Assign words to a key...** copies typed speech into the selected key's draft without replacing its saved sequence until you assign.

Hover explanations cover controls and both pianos. **? Help** opens a built-in guide. Advanced reveals individual phrase sounds, timing and pitch. The GUI was reviewed by a dedicated subagent and its actual rendered screens inspected. New navigation/state/assignment regressions pass. The new workflow still needs user testing in Reason.

All ten speech engines, 42 presets, phrase playback and the previous note-run click fix remain included. No DSP changes in this release.

## Build contents

Ten speech choices: Formant, TI keyboard/chip pitch, SP0256, SC-01A, MEA8000, FOF, Digitalker, FS-inspired 8+8 and Klatt. LPC-10 is a separate mono output codec with approximately 166 ms intentional delay. SID/Amstrad AY carriers, offline typed speech, singing controls, immediate phonetic assignments and MIDI capture/export are included. FS and Klatt have dedicated Engine character panels.

Debug and Release each pass **14/14** automated suites, including phrase timing/retriggers, sustain/channel ownership, state recall, UI assignment and callback allocation guards. Both packaged VST3s pass extracted load/process and checksum checks. Instructions, scope and attribution are included in the ZIP.

Speech data is authored. FS-inspired is an architectural interpretation, not an FS1R firmware/patch/FSeq emulator; Klatt is a reference-backed synthesis port, not DECtalk/Perfect Paul. Full original-hardware or percentage-fidelity equivalence is not claimed. Broader full-DAW and subjective voice-fidelity validation remain unverified.
