# AI Short Drama Cinematic Bench

This repository packages a one-off benchmark for AI short-drama script generation and cinematic key-frame visualization.

Prompt premise:

> A Chinese AI programmer involved in fraud gets lost in a fictional African war zone during militia conflict, escapes, and goes through a personal transformation. The tone should be realist, lightly near-future sci-fi, technical thriller, with a Philip K. Dick-like uncertainty around identity and voice.

## Open

- `index.html` - cinematic stills browser
- `bench-results.html` - script benchmark summary

## Contents

- Four generated scripts:
  - DeepSeek v4 Flash: `pi-deepseek-v4-flash/剧本.md`
  - Opus 4.6: `pi-opus-4-6/剧本.md`
  - Opus 4.8: `pi-opus-4-8/剧本.md`
  - Opus 5: `pi-opus-5/剧本.md`
- One failed model slot:
  - Luna GPT-5.6: `luna-gpt56/失败说明.txt`
- Cinematic image set:
  - 4 casting portraits
  - 16 key stills
  - AI ArtMirror / GPT Image 2

## Notes

The image set is designed as cinematic key stills, not sketch storyboards. Each script has its own casting look, color tone, and four story moments: setup, rupture, moral choice, and ending.

Luna GPT-5.6 did not produce a script because the service returned `503 SETTLEMENT_PRICING_NOT_FOUND`; no replacement model was used.
