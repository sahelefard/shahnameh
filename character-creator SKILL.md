---
name: character-creator
description: Design and generate consistent character profiles, visual descriptions, and reference sheets for Ferdowsi's Shahnameh narratives. Ensures permanent facial and attire consistency across age stages for Poem2Image, Poem2Gif, and Poem2Video in coordination with shahnameh-chronicle-engine and scenery-generator.
---
# Character Creator (Shahnameh Edition)

## Summary

The **character-creator** skill establishes detailed, visually consistent character designs, traits, and prompt tokens based directly on Ferdowsi's descriptions in the Shahnameh. It ensures permanent continuity across static images (`poem2image`), animated loops (`poem2gif`), and full video animations (`poem2video`), coordinating with `shahnameh-chronicle-engine` for age progression and `scenery-generator` for atmospheric harmony.

## Persistence & Consistency Rules (مهم و الزامی)

- **ذخیره‌سازی و حفظ کاراکترها:** این اسکیل با دریافت نام داستان از شاهنامه، مشخصات و کاراکترهای ساخته‌شده را به خاطر می‌سپارد و نباید با دریافت پرامپت‌های جدید، تغییری خودسرانه یا دخل و تصرفی در ویژگی‌های ثابت آن‌ها ایجاد شود.
- **استناد دقیق به متن شاهنامه:** تمامی ویژگی‌های ظاهری، سلاح‌ها و پوشش کاراکترها (مانند ببر بیان، گرز گاوسر، کلاهخود، تاج کیانی و پیشدادی، سیمای رستم، اسفندیار، سهراب، هوشنگ و دیوان) باید دقیقاً منطبق بر توصیفات اشعار فردوسی صورت‌بندی شوند.
- **ثبات چهره:** چهره و ویژگی‌های بصری اصلی هر کاراکتر باید برای همیشه ثابت بماند. تنها تغییر مجاز، تغییرات سنی کاراکتر است که با توجه به `shahnameh-chronicle-engine` و `scenery-generator` اعمال می‌شود.
- **نسخه واحد هر سن:** برای هر کاراکتر در هر بازه‌ی سنی، دقیقاً یک پروفایل و تصویر مرجع واحد ایجاد می‌شود تا ثبات بصری در طول کل اثر حفظ شود.

## When to Use

- Designing heroes, kings, mythical creatures (Simorgh, Div-e Sepid, Black Serpent), and supporting characters from the Shahnameh.
- Preparing consistent character reference prompts for AI image and video generation pipelines.
- Feeding locked character assets into `poem2image` and `poem2video` workflows.

## Steps

1. **Analyze Shahnameh Context:** Extract canonical traits, royal or heroic lineage, emotional state, and specific garments or weaponry described in Ferdowsi's verses.
2. **Consult Chronicle Engine:** Lock the character's exact age stage (youth, middle age, old age) and era-appropriate attire via `shahnameh-chronicle-engine`.
3. **Develop Character Profile:** Define fixed facial structure, beard/hair style, crown or helmet type, armor patterns, and color palette in harmony with `farshchian-miniature-style`.
4. **Output Locked Prompt Tokens:** Provide structured, invariant character descriptors for downstream consumption by `poem2image` and `poem2video`.

## Gotchas

- Never alter a character's core facial identity or signature equipment between shots.
- Ensure all mythical beings (such as Divs or dragons) reflect Persian miniature iconography rather than Western fantasy designs.
