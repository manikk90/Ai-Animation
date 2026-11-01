---
name: latent-reel
description: "A roast-show clip turned into a cartoon, like Samay Raina's India's Got Latent: the guest at the mic on the left, the host reacting on the right, the show's stage behind them. Use when the user asks for a latent-style roast reel or types /latent-reel with a show clip (MP3) with the guest and host talking."
---

# Latent-style roast reel

A roast-show clip turned into a cartoon, like Samay Raina's India's Got Latent: the guest at the mic on the left, the host reacting on the right, the show's stage behind them.

**Input:** a show clip (MP3) with the guest and host talking.
**Run it:** `/latent-reel` and attach or name the file.

## Steps

1. Transcribe the clip with speaker labels and force-align every word. Mark who is talking for every line.
2. Draw a split stage: the guest at a standing mic on a dark curtain on the left, the host behind a desk with a big “H” wall on the right, plus a small show logo in the corner.
3. Draw each person as a flat cartoon that looks like them (hair, beard, outfit, cap) and lip-sync whoever is talking. The other one reacts: smirk, laugh, facepalm.
4. On punchlines, cut to a black screen with “HAHAHA” audience text, or stamp a word like ROASTED.
5. Captions: the language they speak (Hindi or English), 2–4 words, yellow on the spoken word.
6. Render 16:9 and 9:16.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
