---
name: caption-clip
description: Generate subtitles and burn them into videos. Use when the user asks for caption clip or related video work.
---

# Caption Clip

Generate subtitles and burn them into videos.

Category: Video Analysis & Captions (skill #19)

## Workflow

1. Transcribe the audio (word-level timestamps)
2. Generate an SRT/VTT file
3. Review line length and reading speed
4. Burn in with ffmpeg (subtitles filter) using a readable style
5. Export both the burned-in video and the sidecar file

## Notes

- Confirm inputs (source files, brand assets, target platform) before starting.
- Prefer ffmpeg / Remotion / Playwright where available; check they are installed first.
- Keep intermediate and output files in a dedicated project folder.
