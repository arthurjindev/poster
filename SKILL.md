---
name: reposter-share
description: Create a clear, editable Chinese BIM project report poster from DOCX, PDF, PPT, text, or images. Use when Codex needs to extract project content, organize BIM application points, select suitable visual categories, build a blue-white technical poster in HTML/CSS, PPT, PDF, Figma, or Illustrator, and export a presentation-ready PNG or PDF.
---

# Reposter Share

Create a complete, editable BIM report poster suitable for ordinary presentation and review. Prioritize correct content, clear hierarchy, clean technical styling, and a dependable production process.

## Core Rules

- Build the poster with HTML/CSS, PPT, PDF, Figma, Illustrator, or another editable layout tool.
- Keep Chinese text, project facts, captions, dimensions, and labels editable.
- Use CSS, SVG, or vector shapes for frames, title tabs, arrows, icons, borders, and dividers.
- Do not generate the complete poster as one AI image.
- Do not place unverified facts into the poster. Mark missing engineering information as `待补充`.
- Do not place raw software interfaces, watermarks, or irrelevant document chrome in the final poster.
- Do not ask an image model to generate Chinese text, dimensions, project names, logos, or labels.

## Workflow

### 1. Read the source

Extract:

- project name
- location
- building area
- function or use
- BIM application points
- project highlights or results
- available image categories

Preserve verified source facts. Mark missing location, area, or other important engineering data as `待补充`.

### 2. Condense the copy

Convert the source into:

- one main title
- one short value statement
- three to five project facts
- four to six BIM application points
- one project explanation or key-results module
- three to four image-card titles

Keep the language factual, concise, formal, and easy to scan. Do not invent achievements or exaggerate claims.

Read `references/content-mapping.md` when mapping long source material into poster modules.

### 3. Classify and select images

Inspect the source images and classify useful material as:

- project architecture or real scene
- BIM integrated model
- MEP model
- civil or structural model
- local node
- section or cutaway
- clear-height analysis
- point cloud
- optimization comparison
- construction layout

Select one main image and three to four supporting images. Prefer images that directly support the written BIM application points.

### 4. Improve visual material

Clean, crop, or recreate images that are blurry, cluttered, or dominated by software interfaces.

When recreating an image:

- preserve the original project type and technical intent
- preserve important model categories and visible relationships
- avoid obviously incorrect structures or pipe relationships
- use a clean blue-white technical presentation mood
- reject fake text, watermarks, UI bars, distorted geometry, and irrelevant objects

Use generated visuals only as independent image panels. Add all text and annotations later in the layout.

Read `references/image-rendering.md` for general quality principles. Choose generation wording and technical settings according to the available image tool and source material.

### 5. Build the layout

Use this baseline structure unless the source strongly suggests another:

1. Header: organization mark, project title, and short subtitle.
2. Main area: one large project or BIM visual.
3. Left column: project overview and BIM applications.
4. Right panel: project explanation, key results, or optimization summary.
5. Bottom strip: three to four result-image cards.
6. Footer: short summary or organization information.

Keep module edges aligned, spacing consistent, and the title hierarchy obvious.

### 6. Apply basic visual design

- Use blue, white, and pale gray as the main palette.
- Use deep blue for primary title bars.
- Use white or pale-blue information cards.
- Use technical lines, simple icons, arrows, and borders sparingly.
- Keep repeated cards visually consistent.
- Avoid excessive glow, gradients, decoration, and marketing-style effects.

Read `references/style-guide.md` for the shared visual baseline.

### 7. Export and check

Export at the requested final dimensions without enlarging a smaller finished image.

Deliver when practical:

- one editable source file
- one PNG or PDF preview/final output

Check:

- project text matches the verified source
- missing facts are clearly marked
- Chinese text is readable
- images contain no watermarks or software interface bars
- modules are aligned
- title hierarchy is clear
- the main content remains recognizable at thumbnail size
- important text remains editable

## Output Scope

This shared workflow targets clean, presentation-ready BIM posters. Adapt dimensions, rendering settings, visual-generation prompts, layout ratios, and export methods to the user's tools and source quality.

Do not claim that the workflow guarantees production-grade ultra-high-resolution output, exact replication of a private reference, or identical results across different image-generation and layout environments.

