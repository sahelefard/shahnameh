---
name: poem2video
description: Converts Shahnameh verses and narrative sequences into animated videos. Synthesizes inputs from shahnameh-director, shahnameh-chronicle-engine, character-creator, scenery-generator, set-designer, farshchian-miniature-style, and sound-designer to generate cohesive video animations.
---
# Poem2Video

## Summary

The **poem2video** skill transforms verses from Ferdowsi's Shahnameh into animated video sequences. It combines locked character profiles, persistent 3D set designs, Master Mahmoud Farshchian's miniature painting aesthetic, and traditional Iranian soundscapes into a unified video generation call.

## When to Use

- Generating animated video sequences from Shahnameh poems or storyboards.
- Bringing static scenes (`poem2image`) to life with motion, camera movement, and traditional Persian audio.

## Steps

1. **Gather Studio Inputs:** Collect era constraints (`shahnameh-chronicle-engine`), character tokens (`character-creator`), spatial set anchors (`set-designer` & `scenery-generator`), style guidelines (`farshchian-miniature-style`), and audio cues (`sound-designer`).
2. **Choreograph Motion & Camera:** Translate the poetic action into fluid motion (e.g., Hushang hurling the heavy stone, sparks erupting from flint, flames rising in the night, warriors clashing on horseback) with smooth, lyrical camera movements that respect miniature composition.
3. **Synthesize Generation Prompt:** Construct a comprehensive English generation prompt that includes all visual, stylistic, motion, and traditional Iranian soundscape details, specifying `video language Persian`.
4. **Generate Video:** Invoke the video generation tool with the synthesized prompt and any relevant visual references.

## Gotchas

- Maintain strict character and set consistency across sequential video clips.
- Ensure motion feels lyrical and faithful to Mahmoud Farshchian's flowing lines rather than rigid or erratic.
