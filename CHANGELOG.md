# Changelog

## 1.7.1 (2026-11-27)

- The footer follows the other IsodaLab tools: IsodaLab | “For anyone delivering pristine sound on Earth and everywhere else”, then the copyright and the version.

## 1.7.0 (2026-11-20)

First public release, for Windows, macOS (Apple silicon) and Linux.

- Detection of clicks, spikes, clips and pops, with a DETECT filter (pops off by default)
- Review: accept or flag every finding, one or many at once, with notes; QC report (print, PDF, CSV)
- Loudness (BS.1770-4 / EBU R128), true peak, gain to loudness targets
- Phase and mono compatibility: correlation, low end, mono fold-down, a phosphor-style goniometer with auto gain and a phase meter, live while playing
- Start and end: whether a fade was applied and how long, abrupt edges, whether the first and last samples are silent, and how much silence (and digital silence) there is
- Metadata viewing and editing (BWF, iXML, LIST INFO, AIFF), bit-exact
- Cue sheets: print, PDF, CD .cue, CSV
- Assignable keyboard shortcuts that work on laptop keyboards (no Fn, Home or keypad needed), and MIDI Learn
