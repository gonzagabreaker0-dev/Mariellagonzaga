---
name: claude-video-vision
description: Let Claude watch videos and suggest improvements. Use when the user asks for claude video vision or related video work.
---

# Claude Video Vision

Let Claude watch videos and suggest improvements.

Category: Video Analysis & Captions (skill #17)

## Workflow

1. Extract frames at regular intervals plus scene changes
2. Review frames and audio transcript together
3. Assess hook, pacing, clarity, visuals, and audio
4. Return prioritized, timestamped suggestions
5. Offer to apply the top fixes

## Notes

- Confirm inputs (source files, brand assets, target platform) before starting.
- Prefer ffmpeg / Remotion / Playwright where available; check they are installed first.
- Keep intermediate and output files in a dedicated project folder.
