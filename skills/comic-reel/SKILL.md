---
name: comic-reel
description: "A famous movie scene retold as a comic book, like the Drishyam 3 reel: halftone panels, speed lines, BOOM bursts and speech bubbles for every line of dialogue. Use when the user asks for a comic book reel or types /comic-reel with the scene's dialogue audio (MP3)."
---

# Comic book reel

A famous movie scene retold as a comic book, like the Drishyam 3 reel: halftone panels, speed lines, BOOM bursts and speech bubbles for every line of dialogue.

**Input:** the scene's dialogue audio (MP3).
**Run it:** `/comic-reel` and attach or name the file.

## Steps

1. Transcribe the dialogue and split it into panels, one panel per line, with who says it and how (angry, calm, shocked).
2. Draw each character as a bold comic portrait: thick black outlines, flat colours, halftone dot shading.
3. Every panel gets a bright background (orange, green, purple, yellow) with radiating speed lines that pulse on the line's loudest word.
4. Put the dialogue in a white speech bubble with comic lettering, the key word in red. Slam a BOOM, POW or burst sticker on dramatic beats.
5. Cut between panels with a quick comic-page flip or a zoom-punch, with a thick black frame around the whole video.
6. Render 16:9 and 9:16.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
