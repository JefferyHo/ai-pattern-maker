---
name: ai-pattern-maker
description: Guide original flat graphic pattern design from user inspiration, keywords, themes, or reference images, with bilingual English/Chinese support. Use when the user asks for AI-assisted flat pattern design, graphic pattern concepts, visual motifs, surface graphics, design inspiration, master or movement style references, image-generation prompts for a graphic pattern, work titles, design concepts, 平面图案设计, 图案设计, 纹样, 主视觉, 潮流图案, 设计灵感, 大师风格参考, 作品名称, or 设计理念. The skill first clarifies or infers the inspiration, offers multiple style directions to choose from, then produces original pattern directions, prompts, and practical risk guidance.
---

# AI Pattern Maker

Use this skill to turn a user's inspiration into an original flat graphic pattern. Do not bind the workflow to a fixed medium such as apparel, posters, packaging, or screens unless the user specifies one.

## Principles

- Treat the user's idea as raw inspiration, not as a finished brief.
- Offer style directions before execution when the user has not chosen a style.
- Reference movements, design languages, and broad visual traits; do not instruct the model to copy a specific artist's exact expression.
- Keep concrete brands, logos, slogans, private references, and customer-specific examples out of the reusable skill.
- Build original visual systems from composition, shape grammar, line language, color, texture, and symbolism.
- Surface practical risks early: trademark confusion, copyrighted characters, direct artist pastiche, copied layouts, stock assets, unlicensed fonts, and print complexity.
- Match the user's language. Reply in Chinese when the user writes in Chinese; reply in English when the user writes in English. If the user asks for bilingual output, provide English and Chinese sections.

## Workflow

### 1. Understand the Brief

Identify the minimum useful inputs:

- Theme or inspiration: object, emotion, event, phrase, story, audience, or reference image.
- Intended use: generic pattern, apparel, poster, sticker, packaging, social graphic, badge, background, or unknown.
- Tone: playful, premium, rebellious, futuristic, cute, minimal, cultural, technical, handmade, etc.
- Constraints: no text, required text, color limits, production method, brand/logo rules, copyright sensitivity.

If the user provides enough to proceed, state reasonable assumptions briefly and continue.

### 2. Offer Style Directions First

When the user has not chosen a style, provide 3-5 materially different directions. Each option should include:

- Direction name
- Reference movement, school, or broad master category
- Visual traits
- Why it fits the user's inspiration
- Risk note if relevant

Recommended reference categories:

- **Swiss Grid / International Typographic Style**: precise grids, hierarchy, restraint, rational spacing.
- **Bauhaus / Constructivist Geometry**: geometric tension, simple forms, strong diagonals, modular construction.
- **Street Symbol / Graffiti Linework**: marker lines, stencil, spray, stickers, public-space symbols; avoid copying signature characters.
- **Futurist Industrial / Concept Design**: machinery, infrastructure, light paths, city systems, hardware silhouettes; avoid specific copied scenes.
- **Editorial Order / Music-Graphic Minimalism**: coded systems, spacing, typographic rhythm, restrained mystery; avoid direct album-cover layouts.
- **Manga Energy / Cyberpunk Linework**: speed lines, dense urban tech, energy arcs, graphic motion; avoid recognizable characters or panels.
- **Organic Psychedelic Pattern**: flowing forms, optical repetition, color vibration; watch legibility and print complexity.
- **Folk / Vernacular Symbol System**: hand-cut shapes, textile rhythm, local motifs; verify cultural sensitivity.
- **Data / Generative Systems**: algorithmic grids, node maps, particles, modular icons; good for technology or systems themes.

Recommend a default direction if the user is unsure.

### 3. Build the Pattern System

After the user chooses a direction, define:

- **Main form**: symbol, loop, totem, field, modular grid, radial system, creature-like abstraction, typographic structure, or repeat tile.
- **Composition**: centered, diagonal, radial, asymmetric, dense field, border frame, emblem, scattered constellation, or all-over repeat.
- **Graphic elements**: icons, abstract marks, lines, dots, textures, negative space, micro-symbols, geometric modules.
- **Color**: palette, contrast logic, number of colors, production limits if relevant.
- **Texture**: clean vector, screenprint grain, spray dots, risograph offset, halftone, hand-drawn wobble, glitch, paper cut.
- **Text policy**: no text, microtext only, title integrated, or full typographic system.

Keep the design original. Use references to guide decisions, not to replicate exact works.

## Default Output Format

After style selection, use this structure:

```markdown
**Title Options**
- <short title>
- <short title>
- <short title>

**Design Concept**
<brief concept, usually under 300 words if the user does not specify>

**Pattern Direction**
- Main visual:
- Composition:
- Graphic elements:
- Color:
- Texture:
- Production notes:

**Image Generation Prompt**
<structured prompt suitable for image generation>

**Risk Notes**
- <copyright/trademark/style/production risks>
```

For Chinese users, use this structure:

```markdown
**作品名称备选**
- <短名称>
- <短名称>
- <短名称>

**设计理念**
<简洁说明；如用户未指定，通常控制在 300 字以内>

**图案方案**
- 主视觉：
- 构图：
- 图形元素：
- 色彩：
- 质感：
- 落地建议：

**图像生成提示词**
<可直接用于图像生成的结构化提示词>

**风险提示**
- <版权/商标/风格/制作风险>
```

If the user only asks for style options, provide only the style options and wait for a choice.

If the user asks for direct image generation, use the available image generation tool after style and constraints are sufficiently clear.

## Image Prompt Template

```text
Use case: stylized-concept
Asset type: original flat graphic pattern design
Primary request: <theme and user intent>
Style/medium: <chosen direction described by traits, not "copy artist X">
Composition/framing: <centered/radial/grid/repeat/asymmetric/etc>
Subject/graphic system: <main motifs and how they combine>
Color palette: <colors and limits>
Materials/textures: <vector, grain, spray, halftone, hand line, etc>
Text: <none / exact text / microtype only>
Constraints: original design, editable/vector-friendly if needed, intended medium if known
Avoid: copied logos, recognizable copyrighted characters, direct artist imitation, watermark, random text
```

## Risk Rules

- Do not claim a design is legally cleared. Say it is a practical risk assessment, not legal advice.
- Avoid prompts that ask to create an exact living-artist style or a specific protected work.
- For brand/logo use, ask for official vector assets and permission context when faithful reproduction is needed.
- For contest or commercial use, recommend replacing AI-generated approximations of logos, fonts, and brand marks with official licensed files.
- For print, flag overly fine dots, thin lines, gradients, too many colors, and low-resolution raster assets.
- Distinguish between the skill license and output rights: the repository license covers the skill files only, not third-party inputs or generated outputs.
- When users ask about legal safety, identify risk categories and recommend qualified legal review for commercial, contest, or brand-sensitive use.

## Naming and Concept Writing

- Keep names short when requested.
- Prefer active, future-facing, image-rich words.
- Avoid generic titles unless they fit the concept.
- Offer multiple options when the user is exploring.
- Keep concepts concise and mention theme, visual method, symbolism, and emotional outcome.
