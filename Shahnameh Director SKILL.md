---
name: shahnameh-director
description: Central orchestrator and director for the Shahnameh animation and illustration studio. Coordinates shahnameh-chronicle-engine, character-creator, scenery-generator, set-designer, farshchian-miniature-style, sound-designer, poem2image, and poem2video to produce visually and narratively consistent epic adaptations of Ferdowsi's Shahnameh.
---
# Shahnameh Director

## Summary

The **shahnameh-director** skill acts as the central orchestrator for all Shahnameh visual and audiovisual adaptations. It parses Ferdowsi's verses, determines the dramatic tone, and delegates tasks across the studio pipeline while enforcing strict visual, temporal, and auditory continuity.

## When to Use

- Directing full scenes, sequences, or single frames from Ferdowsi's Shahnameh.
- Coordinating multiple studio skills (`shahnameh-chronicle-engine`, `character-creator`, `scenery-generator`, `set-designer`, `farshchian-miniature-style`, `sound-designer`, `poem2image`, `poem2video`).
- Translating epic Persian poetry into structured storyboards, image prompts, and video generation prompts.

## Steps

1. **Analyze the Verses:** Parse the input verses from the Shahnameh to extract key actions, characters, emotional tone (epic battle, tragic loss, royal celebration, mystical discovery), and narrative progression.
2. **Consult the Time Engine (`shahnameh-chronicle-engine`):** Identify the exact mythological or historical era (Pishdadian, Kayanian, Ashkanian, Sasanian), character ages, and era-appropriate armor, crowns, tools, and architecture.
3. **Lock Character & Set Continuity (`character-creator` & `set-designer`):** Retrieve or establish permanent character profiles and 3D spatial set designs so facial features, garments (such as Babr-e Bayan), and environmental landmarks remain unchanged across shots.
4. **Enforce Artistic & Sonic Direction (`farshchian-miniature-style` & `sound-designer`):** Apply Master Mahmoud Farshchian's miniature aesthetic (fluid lines, jewel-toned palettes, spiritual lighting) and pair the visual sequence with traditional Iranian instrumentation (tonbak, daf, ney, santur, setar, dotar).
5. **Execute Output (`poem2image` / `poem2video`):** Synthesize all parameters into a unified, detailed prompt for static key art or animated video generation.

## Gotchas

- Never allow visual jumps or changes in character facial features or set architecture between consecutive prompts unless explicitly dictated by the passage of time in `shahnameh-chronicle-engine`.
- Always ground visual descriptions in authentic Shahnameh text rather than generic fantasy tropes.
