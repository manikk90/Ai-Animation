---
name: personal-explainer
description: "An explainer in your own voice, like “How will the Tesla fly?”: real footage with credit, clean diagrams that build step by step, numbers that pop, and you as the narrator. Use when the user asks for a personal explainer or types /personal-explainer with your voiceover MP3, the topic, and any source links."
---

# Personal explainer

An explainer in your own voice, like “How will the Tesla fly?”: real footage with credit, clean diagrams that build step by step, numbers that pop, and you as the narrator.

**Input:** your voiceover MP3, the topic, and any source links.
**Run it:** `/personal-explainer` and attach or name the file.

## Steps

1. Fact-check the topic from the links and split the voiceover into 3–4 “raaz” (secrets), each with a chip like RAAZ #1 · ULTA CHIPAKNA.
2. Use real footage of the subject where it exists, always with a small “Footage: source” credit, and darken it so the graphics read.
3. Draw a clean diagram for each idea that builds piece by piece as you say it: arrows for airflow, a tank with a pressure number, labels on the parts.
4. Pop big numbers on the word (7,145 PSI, x300!) and NA ✗ chips for what it is not (NA VFX ✗, NA RASSI ✗).
5. Add 2–3 word captions with the active word highlighted, and a hook question at the start.
6. Render 9:16 and 16:9.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
