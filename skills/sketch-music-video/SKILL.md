---
name: sketch-music-video
description: "A pencil-sketch lyric video like Anuv Jain's “Inaam”: soft graphite drawings of the song's story fill the page while the lyrics are handwritten next to them, line by line. Use when the user asks for a sketch music video or types /sketch-music-video with a song MP3 and its lyrics, one sung line per row."
---

# Sketch music video

A pencil-sketch lyric video like Anuv Jain's “Inaam”: soft graphite drawings of the song's story fill the page while the lyrics are handwritten next to them, line by line.

**Input:** a song MP3 and its lyrics, one sung line per row.
**Run it:** `/sketch-music-video` and attach or name the file.

## Steps

1. Separate the vocals with demucs and force-align the lyrics, so every line starts exactly when it's sung.
2. Background: off-white sketchbook paper with soft grain. Title and artist hand-lettered at the top left.
3. For each verse, draw one small scene in thin grey pencil lines (a boy by a window, a shop counter, a room at night). Lines draw on stroke by stroke, with light cross-hatching for shadows.
4. Write each lyric line in a handwritten font in dark pencil, placed beside the drawing it belongs to, letter by letter at the sung time.
5. Keep earlier lines and drawings on the page, slightly faded, so the page fills up like a real sketchbook by the end.
6. Render 16:9 with the song as AAC 256k.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
