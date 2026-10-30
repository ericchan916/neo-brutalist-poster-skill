---
name: neo-brutalist-poster-skill
description: Generate a Simplified-Chinese 9:16 poster in the 「新粗野主义」(neo-brutalist) style by 一张有戏. Use when the user wants a 新粗野主义 / neo brutalist poster.
---

# 新粗野主义 · neo-brutalist poster skill

一张有戏「新粗野主义」风格海报技能。输出一张 9:16 竖版、简体中文的独立海报。

## 用法
1. 确定一个主标题（2–4 字）和一句短句。
2. 画面只出现三段文字：主标题、短句、页脚「一张有戏 · 视觉习作」。
3. 版式可选：big-type-only, diagonal-dynamic。
4. 参照下方完整提示词模板，替换 Headline / Supporting phrase / 场景描述。

## 示例主题
- 开放麦：把声音交给这一刻（big-type-only）— Stark photocopied microphone cutout looming over hard acid-green and black rectangles, heavy compressed Chinese type.
- 破格：边界可以重新安排（diagonal-dynamic）— Giant cropped black Chinese glyphs breaking one hard hot-pink rectangle, visible paper-scanner edges and harsh rules.
- 噪点：把粗粝留在画面里（big-type-only）— High contrast scanned speaker and rough black halftone field on safety-orange paper with brutal type.
- 失序现场：不规则也能形成节奏（diagonal-dynamic）— One stark photocopied overturned metal chair cutout, black chunky type and acid-yellow hard box with broad white break.
- 街头回声：让日常发出自己的声音（big-type-only）— One grainy concrete stair crop and torn blank paper fragment, neon-green field, aggressively offset huge typography.
- 拒绝平庸：让每一次表达有棱角（diagonal-dynamic）— Type-led design, gigantic condensed black glyphs against hot pink, oversized hard border and asymmetric torn black patch.
- 热身：让能量找到一个出口（big-type-only）— One photocopy steel spring diagonally enlarged, acid-yellow/black blocks, compressed type and raw ink grain.
- 继续发生：把未完成变成下一步（diagonal-dynamic）— One high contrast crumpled paper ball and huge cropped type, stark black/white/cobalt rectangles, hard intentional imbalance.

## 完整提示词模板（第 1 张原文）
```
Use case: ads-marketing. Create exactly ONE polished professional 9:16 portrait poster, static flat artwork, Chinese-mainland cultural/creative studio portfolio concept.
Language: Simplified Chinese. Headline: 开放麦. Supporting phrase: 把声音交给这一刻. Tiny plain footer: 一张有戏 · 视觉习作. Exact visible text ONLY these three phrases, every character correctly formed. No English, random numbers, fake events, dates, addresses, awards, offers, prices, affiliations, calls to action or status labels. All content is fictional/conceptual creative brief, no real client claim.

SOURCE UNIVERSAL RULES:


These rules apply to every poster. Do not repeat them in layout or style notes.

- Build around one dominant message, one clear focal point, and one communication goal.
- Establish a simple reading order: headline -> focal image -> supporting copy -> supplied details.
- Preserve required copy exactly unless the user explicitly asks for rewriting.
- Keep important text readable, high-contrast, and inside safe margins.
- Use confident spacing and avoid overstuffed layouts.
- Avoid fake extra text, random logos, QR codes, decorative clutter, malformed typography, and generic AI-poster noise.
- Treat the poster canvas as static print/editorial artwork rather than a clickable interface. If the source explicitly requests a product UI, browser window, dashboard, or device mockup, preserve that depicted content inside the poster.
- CTA copy is extractive-only: include it only when the source explicitly supplies the wording. When output language differs, verify the translated CTA against a recorded exact source quote. Never invent action or status labels.
- If no CTA is sourced, leave the action area empty. If one is sourced, render it as ordinary poster typography in a footer or text lockup. Do not place poster-level action copy inside a button, rounded rectangle, pill, chip, capsule, tab, input field, or any other clickable-looking UI container; do not decorate it with a shadow, arrow, chevron, or cursor icon.



SELECTED STYLE — STRICTLY THIS VISUAL SYSTEM, DO NOT MIX OTHER STYLES:
# Neo-Brutalist

## Intent

Create a raw, confrontational, contemporary poster with loud typography, harsh contrast, visible structure, and intentional anti-polish.

## Typography

- Use heavy sans-serif, compressed type, monospace accents, or rough system typography.
- Let type be oversized, cropped, boxed, repeated, or intentionally awkward.
- Keep critical details readable despite the raw treatment.

## Palette

High-contrast black/white with aggressive accents: neon green, safety orange, hot pink, cobalt, acid yellow.

## Imagery

Use stark cutouts, rough scans, high-contrast portraits, screenshots, grainy photos, or simple brutal blocks.

## Texture / Material

Photocopy grain, screenprint noise, visible borders, rough paper, hard shadows, raw interface-like rectangles.

## Composition Rules

- Use chunky blocks and hard edges.
- Embrace tension, overlap, and deliberate imbalance.
- Make the headline feel immediate and unavoidable.
- Keep source-supplied details in a brutally clear footer. Never turn action copy into a UI label or button.

## Avoid

Polished corporate softness, pastel friendliness, decorative gradients, unreadable chaos, too many stickers, and fake UI clutter.


INTERNAL COMPOSITION:
# Big Type Only

## Composition Structure

- Use typography as the main visual subject.
- Build rhythm through scale, weight, spacing, stacking, and alignment.
- Add minimal supporting shapes, rules, or texture only if they reinforce the type.
- Keep details very compact.

## Hierarchy Rules

1. Main words dominate the page.
2. A source-supplied secondary phrase supports the main claim.
3. Metadata sits as a precise small lockup.

## Text Placement

- Use large type with controlled line breaks.
- Make letter spacing and alignment feel intentional.
- Keep exact text short to reduce rendering risk.

## Image Treatment

No image required. Optional abstract shape, texture, or tiny icon can support mood.

## Spacing Rules

Use margins and line spacing as core design tools. Let type crop or bleed only when still readable.

## Aspect-Ratio Behavior

Excellent in `2:3`, `4:5`, `1:1`, and `9:16`. In `16:9`, use wide word stacks or horizontal rhythm.

## Avoid

Long copy, decorative fonts with poor readability, random letter distortion, and meaningless background graphics.


SPECIFIC SUBJECT AND ART DIRECTION:
Stark photocopied microphone cutout looming over hard acid-green and black rectangles, heavy compressed Chinese type.

Quality: exquisite thoughtful art direction, one immediate focal point, sophisticated typographic spacing and clear reading order, original expressive composition with wide enough safe margins. Headline large and readable at phone thumbnail; secondary text restrained, not generic template. Typography adapted sensitively to real Chinese glyphs, with the visual weight demanded by style. Material/light/print treatment consistent with selected style. If any person appears, fictional mainland Chinese adult, natural anatomy and authentic face; otherwise no people. All props physically coherent unless the SPECIFIC surreal idea deliberately changes physics. No trademarks or label text on products, no fake logos/watermarks/QR. No poster mockup, wall frame, multiple-poster collage, UI buttons or decorative website components. The creative theme must determine composition; vary crop, hierarchy and negative space across the series. Output one finished poster only.
```

全部 8 条提示词见 `PROMPTS.json`，来源见 `SOURCES.md`。
