# Key Finder by W3ird_byt3_beats

[**DOWNLOAD WINDOWS VST3 UPDATE — 0.2.0 (.exe)**](https://github.com/Terpytoine/key-finder-w3ird-byt3-beats/releases/download/v0.2.0-beta/Key-Finder-Setup-0.2.0.exe)

[Release notes, complete source, checksums and sample-test limits](https://github.com/Terpytoine/key-finder-w3ird-byt3-beats/releases/tag/v0.2.0-beta)

![Current interface](https://github.com/Terpytoine/key-finder-w3ird-byt3-beats/releases/download/v0.2.0-beta/Key-Finder-preview-0.2.0.png)

Windows x64 VST3. Darker logo greens, original cryptid background, one centered Freeze button and indicator, always-on reactive fog. The Tonal match/Fit/Ambiguous panel has been removed.

The detector combines whole-session harmonic note evidence with persistent candidate selection. Host BPM/signature/PPQ/bar-start information aligns updates; missing fields stay unavailable. Recent notes are pitch-class evidence, not exact MIDI transcription. Native float and double audio passes through bit-identically: no gain, EQ, dynamics/stereo changes, stretching or added audio latency.

## Install
Run the installer; approve the normal administrator prompt. Restart FL Studio after updating an already loaded instance. Scan with Verify plugins in Options > Manage plugins, then insert Key Finder in a Mixer effect slot. Play from the beginning for at least four bars/eight seconds; twelve seconds without usable host bar timing. A consistent candidate is required, so longer listening can be necessary. Freeze holds the reading. Right-click the panel > Start new analysis after changing songs.

## Beta verification
Native tests and pluginval level 5 pass, including 24 major/minor triads, host timing/changes/missing data, bar/seek/loop clock, stability, Freeze/recall and bit-identical 32/64-bit passthrough. Blue Turtle 77 BPM C# minor piano reaches C# minor with zero changes after its first displayed estimate in the simulated-host pass.

Across twelve labeled one-pass files: four exact label matches, one relative key, three other keys and four short/unstable passes without an estimate. These labels are not independently established ground truth; the complete table and caveats are in SAMPLE_EVALUATION_0.2.0.md inside the source archive. No universal accuracy or certainty claim. Actual FL Studio acceptance and Windows DPI remain pending. The installer is unsigned.

The named Key-Finder-Source-0.2.0.zip asset contains complete corresponding authored source, tests, notices, prompts and exact JUCE source. Do not use the generic GitHub tag-source archive as the full source package. No Cymatics audio/MIDI is distributed. No telemetry or audio upload.
