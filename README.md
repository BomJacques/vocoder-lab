# vocoder-lab
VOCODER LAB effect and instrument VST3 builds for Windows x64.

## Download

**[Download VOCODER LAB 0.4.0 — effect and instrument VST3 ZIP](https://github.com/BomJacques/vocoder-lab/raw/refs/heads/main/downloads/VOCODER-LAB-0.4.0-VST3-win64.zip)**

The ZIP is also visible in the [`downloads`](downloads) folder and on the [0.4.0 release page](https://github.com/BomJacques/vocoder-lab/releases/tag/v0.4.0). A SHA-256 checksum is included alongside it.

## Install

1. Extract the ZIP.
2. Copy the complete `VOCODER LAB.vst3` and/or `VOCODER LAB INSTRUMENT.vst3` folders from `Binaries/Release` to your DAW's VST3 scan location.
3. Rescan or restart the DAW. Use the instrument for keyboard-playable speech; use the effect for audio processing.

Windows x64, VST3 only. No standalone app. Requires the Microsoft Visual C++ x64 runtime. Keep each entire `.vst3` folder together.

## Build contents

TI, SP0256 and SC-01A speech synthesis; SID/Amstrad AY carrier sections; offline typed speech; singing controls; grouped phonetic assignments; 26 presets. Usage and attribution are included in the ZIP.

Development build: Debug and Release each passed 9/9 automated tests, plus extracted VST3 loading/processing checks. Actual Reason sessions and subjective voice fidelity remain unverified. The voices use authored phonemes; complete original hardware emulation is not claimed.
