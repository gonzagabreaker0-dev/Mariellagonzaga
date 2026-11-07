---
name: omni-captions
description: Transcribe, translate, and style video captions. Use when the user asks for omni captions or related video work.
---

# Omni Captions

Transcribe, translate, and style video captions.

Category: Video Analysis & Captions (skill #20)

## Workflow

1. Transcribe in the source language
2. Translate to each requested language, preserving timing
3. Apply a style (font, color, outline, position)
4. Export one caption file per language
5. Optionally burn in a chosen track

## Notes

- Confirm inputs (source files, brand assets, target platform) before starting.
- Prefer ffmpeg / Remotion / Playwright where available; check they are installed first.
- Keep intermediate and output files in a dedicated project folder.
