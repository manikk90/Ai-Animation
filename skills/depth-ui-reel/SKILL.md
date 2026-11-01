---
name: depth-ui-reel
description: "Floating app interfaces that sit behind my head, with my body cut out in front of them. Use when the user asks for a depth ui reel or types /depth-ui-reel with a 9:16 talking-head clip."
---

# Depth UI reel

Floating app interfaces that sit behind my head, with my body cut out in front of them.

**Input:** a 9:16 talking-head clip.
**Run it:** `/depth-ui-reel` and attach or name the file.

## Steps

1. Cut me out of the background on every frame (person segmentation).
2. Draw clean UI cards (chat bubbles, stats, browser windows) between the background and me.
3. Animate the cards in on the words they relate to.
4. Composite me back on top so the UI looks like it's behind my head.

## Every time it runs

- Transcribe my audio with word-level timings, so every graphic lands on the word I say.
- Keep text out of the top 250 px and the bottom 420 px (Instagram buttons and caption).
- Render a 1080×1920 MP4 at 30 fps with my original audio. Never re-grade or filter my face unless the skill says so.
- Show me 3 snapshots before the final render, and ask before overwriting files.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Reel formats
