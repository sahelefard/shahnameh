---
name: set-designer
description: 3D spatial set designer with permanent world memory for Shahnameh narratives. Designs, stores, and maintains consistent architectural layouts, landmarks, and environmental details across scenes, updating sets only when directed by shahnameh-chronicle-engine and shahnameh-director.
---
# Set Designer

## Summary

The **set-designer** skill constructs and permanently remembers spatial layouts, architectural details, and key environmental props for Shahnameh locations. It works alongside `scenery-generator` and `shahnameh-chronicle-engine` to guarantee that recurring locations never lose their established visual details across subsequent prompts.

## When to Use

- Designing and locking recurring sets (such as Alborz mountain passes, the White Div's cavern, Kay Kavus's palace, or the plains of Hamun).
- Maintaining spatial and prop continuity across multi-shot image (`poem2image`) or video (`poem2video`) sequences.
- Applying chronological wear, destruction, or time-of-day shifts to an existing set.

## Steps

1. **Initialize or Retrieve Set:** Check if the narrative location has already been established in the story's world database. If it exists, load all locked spatial landmarks, rock formations, pillars, and color schemes.
2. **Construct Spatial Layout:** Define foreground, midground, and background anchors (e.g., specific black flint boulders, palace columns, tent arrangements, or cavern stalactites).
3. **Apply Temporal State:** Coordinate with `shahnameh-chronicle-engine` to reflect the current time of day (sunset, starlit Sadeh night) or physical alterations caused by story events (e.g., shattered rocks, ignited bonfires).
4. **Export Set Tokens:** Provide fixed environmental descriptors to `poem2image` and `poem2video` so background geometry and details remain consistent from shot to shot.

## Gotchas

- Never omit or randomly alter established set elements in follow-up prompts; persist all prior spatial details automatically unless a narrative event changes them.
