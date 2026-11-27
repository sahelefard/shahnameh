---
name: scenery-generator
description: Design and generate atmospheric mise-en-scene, background settings, lighting, and environmental prompts for Ferdowsi's Shahnameh narratives. Coordinates with set-designer, shahnameh-chronicle-engine, and character-creator for Poem2Image and Poem2Video workflows.
---
# Scenery Generator (Shahnameh Edition)

## Summary

The **scenery-generator** skill analyzes verses from Ferdowsi's Shahnameh to design authentic environmental backdrops, dramatic lighting, and compositional mise-en-scene. It works with `set-designer` and `shahnameh-chronicle-engine` to complement character designs from `character-creator` across `poem2image` and `poem2video`.

## Persistence & Consistency Rules (مهم و الزامی)

- **ثبات فضایی و محیطی بر اساس شاهنامه:** با دریافت ابیات و نام داستان، بسترهای جغرافیایی شاهنامه (مانند کوه البرز، غار دیو سپید، دشت هامون، هفت‌خان و کاخ‌های پیشدادی و کیانی) تثبیت می‌شوند و در پرامپت‌های بعدی نباید تغییرات خودسرانه در کلیت محیط ایجاد شود.
- **هماهنگی با ماشین زمان و طراح صحنه:** این اسکیل با در نظر گرفتن عصر داستانی و سن کاراکتر (از `shahnameh-chronicle-engine` و `character-creator`) و جزئیات ثبت‌شده در `set-designer`، شرایط نوری و جوی متناسب را اعمال می‌کند.

## When to Use

- Designing landscapes, battlefields, mythical caverns, and royal courts from the Shahnameh.
- Establishing dramatic lighting, sky compositions, and atmospheric mood (epic, tragic, mystical, festive).
- Providing environmental prompts that pair seamlessly with character and set tokens.

## Steps

1. **Parse Shahnameh Geography & Mood:** Extract the canonical location, weather, time of day, and dramatic atmosphere from the verses.
2. **Establish Mise-en-Scene:** Arrange spatial depth, army formations, multi-layered rock structures, and symbolic natural elements (cypress trees, swirling clouds, mountain peaks).
3. **Define Lighting & Palette:** Set the lighting scheme (divine golden firelight, twilight indigo, smoky battlefield haze) aligned with `farshchian-miniature-style`.
4. **Sync with Set Designer:** Pass environmental mood and lighting parameters to `set-designer` so permanent spatial landmarks are illuminated consistently.

## Gotchas

- Keep environmental aesthetics rooted in Iranian plateau geography and Persian miniature traditions.
