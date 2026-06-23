# edge-tts — Neural text-to-speech via Microsoft Edge voices

> Turn any text into natural-sounding speech using Microsoft Edge's neural TTS engine. Multiple languages and voices, adjustable rate and pitch, subtitle generation included.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
edge-tts wraps Microsoft Edge's neural TTS through the `node-edge-tts` npm package. For most cases, use the built-in `tts` tool directly. The bundled converter script offers fine-grained control over voice, speed, pitch, and subtitle output. The skill automatically filters TTS trigger keywords out of the text before synthesis so your audio stays clean.

## Features
- **Multiple languages & voices** — broad neural voice catalog
- **Rate control** — `--rate +10%` / `-20%`
- **Pitch adjustment** — shape tone of the voice
- **Subtitle generation** — timed caption output
- **Keyword filtering** — strips trigger words before synthesis
- **Two paths** — built-in `tts` tool (primary) or advanced CLI script

## Usage / Quick Start
```bash
# Advanced control via converter script
node scripts/tts-converter.js "Your text here"   --voice en-US-AriaNeural   --rate +10%   --output output.mp3
```

## Trigger Keywords (OpenClaw)
tts, voice output, text to speech, audio generation, speak text

## Related Skills
- [e-ears](https://github.com/NachaFromMars/e-ears) — audio analysis and music understanding

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
