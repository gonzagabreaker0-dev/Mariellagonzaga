---
name: shorts-video-creator
description: Reframe horizontal videos into vertical Shorts. Use when the user asks for shorts video creator or related video work.
---

# Shorts Video Creator

Reframe horizontal videos into vertical Shorts.

Category: Shorts & Visual Assets (skill #12)

## Workflow

1. Probe the source resolution and aspect ratio
2. Track the speaker/subject and crop to 9:16
3. Fall back to blurred-background letterboxing when cropping loses content
4. Add captions and a title overlay
5. Export under the Shorts length limit

## Notes

- Confirm inputs (source files, brand assets, target platform) before starting.
- Prefer ffmpeg / Remotion / Playwright where available; check they are installed first.
- Keep intermediate and output files in a dedicated project folder.
