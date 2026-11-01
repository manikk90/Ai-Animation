---
name: madhubani-kahani
description: "A Panchatantra-style story told as a living Madhubani painting: double black outlines, patterned fills, fish-scale water and a red-yellow folk border. Use when the user asks for a madhubani kahani or types /madhubani-kahani with a Hindi story voiceover MP3."
---

# Madhubani kahani

A Panchatantra-style story told as a living Madhubani painting: double black outlines, patterned fills, fish-scale water and a red-yellow folk border.

**Input:** a Hindi story voiceover MP3.
**Run it:** `/madhubani-kahani` and attach or name the file.

## Steps

1. Transcribe the story in Devanagari and force-align every word to the voice.
2. Plan one painted scene per line: the place, the characters, and the one action that matters.
3. Paint everything in Madhubani style: bold black double outlines, flat red, yellow, indigo and green, every shape filled with line patterns, inside a thick decorated border.
4. Animate small things on the spoken word: the monkey jumps, the crocodile's jaw snaps, the water ripples.
5. Put dialogue in speech bubbles that pop in on the first spoken word of each line.
6. Render 1920×1080.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
