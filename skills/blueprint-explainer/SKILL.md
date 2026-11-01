---
name: blueprint-explainer
description: "A long YouTube explainer drawn like an engineering blueprint, like the Piramal Finance loan video: a blue grid sheet, white line drawings, and numbers that calculate live as you talk. Use when the user asks for a blueprint explainer or types /blueprint-explainer with a long voiceover MP3 (3–10 minutes) and the facts or numbers it covers."
---

# Blueprint explainer

A long YouTube explainer drawn like an engineering blueprint, like the Piramal Finance loan video: a blue grid sheet, white line drawings, and numbers that calculate live as you talk.

**Input:** a long voiceover MP3 (3–10 minutes) and the facts or numbers it covers.
**Run it:** `/blueprint-explainer` and attach or name the file.

## Steps

1. Transcribe and force-align the voiceover, then split it into sheets, one topic per sheet (Loan amount, Interest, Tenure, CIBIL, Documents…), each with a sheet number in the title block.
2. Style: deep blue blueprint paper with a fine grid, thin white lines, monospace labels, and yellow for the key numbers.
3. Draw every idea as a technical diagram that builds stroke by stroke: a policy file with labelled boxes, a ruler for the loan range, a gauge for the CIBIL score, a flow of steps for the process.
4. When numbers are spoken, show the calculation live: an EMI table filling in, a total counting up, a bar that grows.
5. Captions: 3–5 words at the bottom, the key word in yellow. Keep a small sheet label in the corner the whole time.
6. Render 16:9 for YouTube, plus 9:16 cut-downs of the best minute.

## Every time it runs

- Draw everything in code (an HTML canvas rendered frame by frame in headless Chrome, encoded with ffmpeg). No stock footage or image generators, so the look is the same every time.
- Time every word with forced alignment (torchaudio MMS_FA). Never guess timings.
- Show me a contact sheet of stills before the full render, and ask before overwriting files.
- Render the MP4 with the original audio, plus a 720p copy under 20 MB for WhatsApp.

---
From [aanshai.vercel.app/skills](https://aanshai.vercel.app/skills) · Animated videos
