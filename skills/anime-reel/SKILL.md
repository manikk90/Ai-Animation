---
name: anime-reel
description: "An anime-style episode with original characters drawn in code and lip-synced to your voice lines, like the Zero Se Freelance series. Use when the user asks for a anime reel or types /anime-reel with a script and the voice MP3s for each line."
---

# Anime reel

An anime-style episode with original characters drawn in code and lip-synced to your voice lines, like the Zero Se Freelance series.

**Input:** a script and the voice MP3s for each line.
**Run it:** `/anime-reel` and attach or name the file.

## Steps

1. Read the script and split it into shots: who speaks, where it happens, and the camera move.
2. Draw each character in anime style (big eyes, thick clean outlines, flat colours with one shade) and save a character sheet, so they look the same in every shot.
3. Force-align every voice line and open and close each mouth with the loudness of that character's voice. Add blinks and small idle motion.
4. Add anime tricks on key lines: speed lines, impact frames, screen shake and chibi reactions.
5. Add 2–3 word captions with the spoken word in the speaker's colour, and sound effects on the hits. No background music unless I ask.
6. Render 9:16 for reels and a 16:9 copy for YouTube.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
