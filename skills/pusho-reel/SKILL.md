---
name: pusho-reel
description: "A Puneet Superstar “Baba Pusho” cartoon reel with the full class: Baba Pusho teaching, his students reacting, Hindi captions on every word, a new scene for every line. Use when the user asks for a pusho reel or types /pusho-reel with a Puneet Superstar audio clip (MP3)."
---

# Pusho reel

A Puneet Superstar “Baba Pusho” cartoon reel with the full class: Baba Pusho teaching, his students reacting, Hindi captions on every word, a new scene for every line.

**Input:** a Puneet Superstar audio clip (MP3).
**Run it:** `/pusho-reel` and attach or name the file.

## Steps

1. Transcribe the Hindi in Devanagari with whisper (large-v3), stop and let me fix wrong words, then force-align the corrected text.
2. Use one fixed cast and keep it identical in every episode: Baba Pusho (long white beard, dark cap, saffron shawl) and his students (a footballer in a #7 jersey, a young man in a kurta, an old bearded baba, a Greek marble bust).
3. Plan one scene per line: the classroom with a chalkboard titled “पुशो ज्ञान केंद्र”, temples, a sunset lake, a bridge, a living room. Pusho's mouth moves with the voice, and the students react (laugh, shock, nod).
4. Add a small “पुशो वाणी” badge top-left and pop stickers on key words (RED FLAG, अभागा, 100% STEEL).
5. Captions: Hindi, 3–5 words, spoken word in yellow, on a dark band at the bottom.
6. Render 16:9 and a 9:16 version.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
