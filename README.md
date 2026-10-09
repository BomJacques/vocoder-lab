# longland VOWL

Retro speech instrument and effect for Windows x64.

## Download 0.7.0

Download both VST3s from the [0.7.0 release](https://github.com/BomJacques/vocoder-lab/releases/tag/v0.7.0):

- [Windows VST3 ZIP](https://github.com/BomJacques/vocoder-lab/releases/download/v0.7.0/LONGLAND-VOWL-0.7.0-VST3-win64.zip)
- [SHA-256 checksum](downloads/LONGLAND-VOWL-0.7.0-VST3-SHA256.txt)

Extract the archive and copy the complete **longland VOWL.vst3** and **longland VOWL Instrument.vst3** folders from Binaries/Release to a VST3 scan folder. Replace previous copies with the same IDs, then rescan Reason.

0.7.0 integrates the actual Blender design into both live editors: native metal panels, moulded TI plastic, shallow bevels, wider assignment pianos, glowing CRT text, moving controls and all twenty views. The ZIP includes screenshots of every section under docs/UI-0.7.0.

Ten speech choices, 42 presets, typed words, words-to-keys sequences, immediate phonetic tiles, singing controls, vowel pad, Easy/Advanced and hover Help remain included. Plugin/parameter IDs, presets and the earlier note-run click fix are preserved. No standalone application.

Record notes in Reason's sequencer with Computer Keys or an external MIDI keyboard. The plugin piano auditions sounds. Phrase phonemes are audio, not generated MIDI notes.

Debug and Release each pass 14/14 suites. Both packaged VST3s pass extracted load/process and checksum checks. Actual updated GUI screenshots inspected. User testing in Reason remains pending. Requires Microsoft Visual C++ x64 runtime.

Speech data is authored; complete original devices, vocabulary ROMs, FS1R firmware and DECtalk are not bundled. LPC-10 is a separate mono codec with about 166 ms delay. Read the bundled documentation for engine scope and attribution.
