---
name: audio-editing
description: Clean background noise, improve voices, and balance audio. Use when the user asks for audio editing or related video work.
---

# Audio Editing

Clean background noise, improve voices, and balance audio.

Category: Color, Audio & AI Video Generation (skill #23)

## Workflow

1. Measure loudness and noise floor
2. Denoise, high-pass, and de-ess as needed
3. Apply EQ and gentle compression to voice
4. Normalize to -14 LUFS (or the target platform's level)
5. Duck music under speech and export

## Notes

- Confirm inputs (source files, brand assets, target platform) before starting.
- Prefer ffmpeg / Remotion / Playwright where available; check they are installed first.
- Keep intermediate and output files in a dedicated project folder.
