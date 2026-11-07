---
name: skill-creator-video
description: Build your own custom Claude skills for video creation. Use when the user asks for skill creator (video) or related video work.
---

# Skill Creator (Video)

Build your own custom Claude skills for video creation.

Category: Complete Video Workflows (skill #30)

## Workflow

1. Ask what repeatable video task the skill should automate
2. Draft a SKILL.md with a clear name and trigger-rich description
3. Write concrete step-by-step instructions and any helper scripts
4. Test on a real example and refine
5. Save under .claude/skills/<name>/

## Notes

- Confirm inputs (source files, brand assets, target platform) before starting.
- Prefer ffmpeg / Remotion / Playwright where available; check they are installed first.
- Keep intermediate and output files in a dedicated project folder.
