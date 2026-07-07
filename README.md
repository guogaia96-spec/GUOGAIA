---
name: xhs-packaging-finishing-deck
description: Create Xiaohongshu/Rednote 3:4 vertical carousel decks from local packaging printing, decorative finishing, or material craft videos. Use when the user asks to turn packaging craft videos into 小红书图文, 3:4 PNG/PDF/HTML slides, Apple/CMF style packaging process cards, matching video-frame visuals, three cover options, SEO titles, long-tail keyword copy, pinned comments, or follow CTAs for packaging design and printing craft content.
---

# XHS Packaging Finishing Deck

Use this skill to reproduce the approved workflow from the decorative finishing project: local craft videos become a 3:4 Xiaohongshu carousel, then cover options, then SEO copy.

## Output Contract

Deliver, unless the user asks for a smaller scope:

- A 3:4 vertical carousel, `1080x1440` pages.
- PNG pages plus a PDF. HTML is optional but recommended when the user asks for web-native slides.
- Three cover candidates for the post.
- Xiaohongshu title options, subtitle, post body, SEO long-tail terms, hashtags, pinned comment, and follow CTA.

Use Chinese as primary copy. Use English only as a small secondary design layer.

## Core Workflow

1. Read local videos and existing extracted assets.
2. Restructure content into no more than 12 pages unless the user requests otherwise.
3. Draft a page outline first when the user asks to confirm before final generation.
4. Extract candidate frames from each video.
5. Match every page to a corresponding full-frame process or product image.
6. Render the 3:4 carousel with the locked visual system.
7. Generate three covers with different click strategies.
8. Generate SEO-rich Xiaohongshu copy.

For detailed rules, read:

- `references/visual_workflow.md` before generating PNG/PDF/HTML.
- `references/xhs_seo_copy.md` before generating titles and post copy.

Use `scripts/extract_frame_candidates.py` when fresh candidate frames are needed.

## Page Structure

Use this sequence for packaging decorative finishing education:

1. Problem / hook.
2. Concept / selection logic.
3. Process map.
4. Raised form: embossing, texture, foam.
5. Light control: foil, refraction, holographic/glitter.
6. Surface contrast: UV, matte, reverse varnish.
7. Crackle texture: wrinkle, ice flower.
8. Tactility: flocking.
9. Structure: die-cut.
10. Application by category.
11. Production risk.
12. Summary.

Each page should include:

- Slide Type.
- Bilingual title.
- 3-5 short Chinese lines with secondary English.
- One corresponding full-frame image.
- One short red/gold takeaway line.

## Visual Rules

Use the proven layout:

- Canvas: `1080x1440`, strict 3:4.
- Background: `#F7F5F3`.
- Text: `#111111`.
- Accent red: `#8B0000`.
- Accent gold: `#D4AF37`.
- Hairline: `#D8D1C8`.
- Image area: about 40% of page height.
- Text area: about 60% of page height.
- Safe margin: keep all four edges visually consistent, about 76px.
- Do not use collage boards unless no good full-frame material exists.
- Prefer full product/process images from the matching craft video.
- Avoid frames that are mostly title slides, black lecture screens, or dense in-video text.

Typography:

- Chinese title: heavy black sans style, e.g. Founder Lanting Hei if available, otherwise SimHei.
- Chinese body: Source Han Sans / Noto Sans SC.
- English: EB Garamond or Times-style serif.
- Keep title bold enough. Do not use thin hero type for this style.

## Image Matching Rules

Never treat images as decoration. Match by craft:

- 凹凸 / 压纹 / 发泡: use raised surfaces, dies, paper height, textured samples.
- 烫金 / 折光 / 七彩彩葱: use reflective metal, foil, optical lines, glitter/holographic samples.
- UV / 磨砂 / 逆向上光: use gloss-matte contrast, varnish samples, coating machinery if better than a text slide.
- 皱纹 / 冰花: use crackle, crystalline, rough surface macro.
- 植绒: use velvet/fiber texture or flocked packaging.
- 镂空: use die-cut windows, laser/cutting scenes, finished paper structure.
- 注意事项: use production, testing, registration, cutting, or factory process frames.

If a chosen frame contains subtitles but the visual is still the best process evidence, it is acceptable. If the frame is mostly words, replace it.

## Cover Strategy

Generate three 3:4 cover options:

- A: 收藏型教程, e.g. `12页讲透装饰工艺`.
- B: 痛点钩子, e.g. `高端包装为什么显贵？`.
- C: 观点型, e.g. `别再乱用装饰工艺`.

Use the same palette and typography as the carousel. Prefer strong full-frame product/process photos. Avoid making covers look like generic PPT title pages.

## Validation

Before final response:

- Confirm page count.
- Confirm PNG pages exist.
- Confirm PDF exists.
- Open at least 2-3 representative PNGs: cover/early page, a middle process page, a risk or summary page.
- Check image/text ratio is about 40/60.
- Check margins are consistent.
- Check no page uses an unrelated image.
- Check Chinese text does not render as missing glyph boxes.

Report final paths clearly.
