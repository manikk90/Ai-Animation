---
name: personal-broll-library
description: "Search my own B-roll folder in plain English ('me walking at night') and return the best matching clips. Use when the user asks for a personal b-roll library or types /personal-broll-library with a folder of my B-roll clips."
---

# Personal B-roll library

Search my own B-roll folder in plain English ("me walking at night") and return the best matching clips.

**Input:** a folder of my B-roll clips.
**Run it:** `/personal-broll-library` and attach or name the file.

## Steps

1. Go through every clip in the folder and sample frames.
2. Write a short description of each clip (place, action, mood, time of day) into an index file.
3. When I ask for a scene in plain English, return the 3 best matching clips with timestamps.
4. Keep the index updated when I add new clips.

## Every time it runs

- Transcribe my audio with word-level timings, so every graphic lands on the word I say.
- Keep text out of the top 250 px and the bottom 420 px (Instagram buttons and caption).
- Render a 1080×1920 MP4 at 30 fps with my original audio. Never re-grade or filter my face unless the skill says so.
- Show me 3 snapshots before the final render, and ask before overwriting files.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Reel formats
