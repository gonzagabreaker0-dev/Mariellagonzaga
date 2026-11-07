---
name: watch-video
description: Analyze scenes, pacing, and transcripts. Use when the user asks for watch video or related video work.
---

# Watch Video

Analyze scenes, pacing, and transcripts.

Category: Video Analysis & Captions (skill #18)

## Workflow

1. Transcribe the audio with timestamps
2. Detect scene cuts and compute average shot length
3. Summarize structure: intro, body, outro
4. Flag slow sections, filler words, and dead air
5. Output a timeline report

## Notes

- Confirm inputs (source files, brand assets, target platform) before starting.
- Prefer ffmpeg / Remotion / Playwright where available; check they are installed first.
- Keep intermediate and output files in a dedicated project folder.
