---
name: lyric-video
description: "A hand-drawn crayon lyric video on a dark chalkboard: every word writes on as it's sung, and each line gets its own little drawing. Use when the user asks for a crayon lyric video or types /lyric-video with a song MP3 and its lyrics, one sung line per row."
---

# Crayon lyric video

A hand-drawn crayon lyric video on a dark chalkboard: every word writes on as it's sung, and each line gets its own little drawing.

**Input:** a song MP3 and its lyrics, one sung line per row.
**Run it:** `/lyric-video` and attach or name the file.

## Steps

1. Separate the vocals with demucs, force-align the lyrics to them, and find the beats with librosa.
2. Write each word on letter by letter at its exact sung time, in mixed playful fonts and a pastel crayon palette on a dark navy board.
3. Mask every stroke with a crayon grain texture and re-jitter it 8 times a second, so it looks hand-drawn.
4. Draw one simple doodle per line, stroke by stroke: a moon, a globe, a lightning bolt, a heart tunnel.
5. Pop and shake on the beats, and clear the board just before the next line starts.
6. Render 16:9 with the song as AAC 256k.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
