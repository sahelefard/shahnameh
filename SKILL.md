---
name: shahnameh-chronicle-engine
description: Temporal and chronological engine for Ferdowsi's Shahnameh. Tracks mythological and historical eras (Pishdadian, Kayanian, Ashkanian, Sasanian), character aging stages, and era-appropriate weapons, clothing, and architecture to ensure strict chronological continuity across scenes.
---
# Shahnameh Chronicle Engine

## Summary

The **shahnameh-chronicle-engine** skill manages the timeline, eras, and character aging across Ferdowsi's Shahnameh. It provides temporal parameters to `character-creator`, `scenery-generator`, and `set-designer` so every scene reflects its exact point in the epic's chronology.

## When to Use

- Determining the era, technology level, and cultural aesthetic of a Shahnameh story.
- Tracking a character's exact age stage (e.g., Rostam in his youth during the Seven Labors, middle age against Esfandiyar, or old age during Sohrab's tragedy).
- Updating recurring locations over decades or centuries in coordination with `set-designer`.

## Steps

1. **Identify the Era:** Classify the narrative into its proper Shahnameh period:
   - **Pishdadian Era:** Dawn of civilization, discovery of fire and iron (Keyumars, Hushang, Tahmuras, Jamshid, Fereydun, Manuchehr). Early royal crowns, primal stonework, natural mountain altars.
   - **Kayanian Era:** Peak heroic and chivalric age (Kay Kavus, Kay Khosrow, Rostam, Sohrab, Siavash, Esfandiyar). Elaborate armor, Babr-e Bayan, ox-headed maces (Gorz-e Gavsar), grand palaces, and organized armies.
   - **Historical/Sasanian Era:** Late imperial grandeur, intricate courtly attire, and fortified castles.
2. **Determine Character Age Stage:** Output the exact age bracket and physical maturity of each character at the moment of the verse, passing this lock to `character-creator`.
3. **Log Temporal Progression:** Inform `set-designer` and `scenery-generator` of time of day, seasonal shifts, or multi-year gaps that affect environmental wear, lighting, or architectural evolution.

## Gotchas

- Do not mix anachronistic armor or architectural styles from later eras into early Pishdadian scenes.
- Keep character aging strictly tied to the canonical sequence of the Shahnameh.
