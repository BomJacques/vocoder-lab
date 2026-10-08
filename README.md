# Longland L'RNX

Retro speech instrument and effect for Windows x64, previously called VOCODER LAB.

## Download 0.6.2

Download the [VST3 ZIP](downloads/LONGLAND-LRNX-0.6.2-VST3-win64.zip) and [checksum](downloads/LONGLAND-LRNX-0.6.2-VST3-SHA256.txt), or use the [GitHub release](https://github.com/BomJacques/vocoder-lab/releases/tag/v0.6.2).

Extract the archive and copy both complete bundles from Binaries/Release to your VST3 scan folder: **Longland L'RNX.vst3** and **Longland L'RNX Instrument.vst3**. Replace earlier VOCODER LAB bundles to avoid duplicate copies with the same IDs, then rescan Reason. Presets and plugin IDs are preserved.

0.6.2 adds the new branding and removes Record/Save MIDI controls. Record notes in Reason's sequencer using Reason Computer Keys or an external MIDI keyboard. The plugin piano auditions sounds. Help has been updated.

The new mechanical Blender faceplate is a separate design asset; this release uses the existing JUCE interface with the new name. No standalone app. Requires the Microsoft Visual C++ x64 runtime.

Ten speech choices, 42 presets, typed words, words-to-keys sequences, rounded sound tiles, singing controls, vowel pad, Easy/Advanced and hover Help remain included. No DSP changes; the existing note-run click fix remains.

Debug and Release each pass 14/14 suites. Both packaged VST3s pass extracted load/process and checksum checks. User testing in Reason remains pending. Speech data is authored; full historical devices, original vocabulary ROMs, FS1R firmware and DECtalk are not bundled. LPC-10 is a separate mono codec with about 166 ms delay. See the included documentation for scope and attribution.
