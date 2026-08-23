# Visual Asset Standard v3.2

## Core rule

Actual visual assets are part of the article deliverable. A placeholder, image plan, filename suggestion, or generic collage is not a delivered image.

## Visual strategy before production

For every main content section, define one primary visual job:

- Problem identification.
- Scenario overview.
- Decision workflow.
- Method operation.
- Before/after or comparison.
- Product experience.
- Outcome, preservation, or sharing.

Create a visual map with `templates/visual_asset_map.md` before making or sourcing images.

## Minimum asset requirements

- Introduction: pain point or outcome visual when it improves comprehension.
- Quick Answer: compact decision/workflow visual.
- Every main solution/method: at least one scenario or method visual.
- A featured direct-product section: a product-experience, workflow, or result-comparison visual.
- Each asset must be embedded in the final document and separately delivered as an image file.

The delivery contract must define whether a summary, FAQ, or Verdict also requires a visual. Do not leave “every section” ambiguous.

## Best-for and scenario visuals

- Every main solution must have a concise `Best for` block containing three recognizable scenarios.
- Where several scenarios help readers self-identify, use one visual-first scenario overview with only short labels.
- Do not use a white-background text-heavy card or generic arrow graphic when a concrete user scenario, product state, clip state, or before/after visual would serve better.

## Scene fit and visual quality: hard gate

An asset must help the reader recognize the actual situation addressed by its section. Before production, record the reader, task, setting or product state, and decision/outcome in the visual map.

- Prefer a credible, topic-specific scene: for example, the relevant creator, researcher, editor, device, media state, or product workflow.
- Use text only as a short supporting label. A visual made chiefly of black text on a white background, a generic flow arrow, or a decorative collage fails this gate when a real scene or state would better explain the user need.
- Do not reuse the same generic composition across sections. Each asset must perform the distinct visual job recorded for that section.
- Do not invent branded interfaces, product results, or before/after claims. Use an abstract but recognizable workflow or clearly label an illustration when exact UI proof is unavailable.
- Assess visual style for topic and audience fit, composition, legibility, and an intentional colour/material treatment before embedding it.

## Aspect ratio and placement: hard gate

The document frame must adapt to the asset, never the other way around.

- Record the source image dimensions and native aspect ratio before placement.
- Preserve that ratio when sizing the inline image. Do not independently set width and height from a pre-existing image frame.
- Do not silently crop a scene to make it fit. Any crop must retain the visual's stated subject and be recorded in the map with a reason.
- After embedding, verify the displayed width/height ratio against the source ratio. Allow only rounding-level variance (at most 1%).
- If the page needs a different layout, resize proportionally, move the image, or create a deliberately composed alternative. Do not stretch, squash, or clip the image.

## Steps: default image pattern

- Default: one method = one compact composite step visual, for example `Find -> Select -> Fix -> Export`.
- Use step-by-step individual images only when the operation is high risk, materially different at each step, or needs precise UI confirmation.
- Do not create multiple large images that repeat the same explanation.
- Preserve useful original visuals; additions should fill a new visual task, not replace them only for style consistency.

## Quality requirements

Each asset needs:

- A unique filename suitable for SEO.
- Accurate, descriptive Alt text; no keyword stuffing.
- A caption that explains the reader benefit.
- A documented insertion point and corresponding section.
- A visual style appropriate to the audience, product type, and article topic.
- No placeholder text, unreadable dense text, irrelevant scene, watermark, clipped subject, or invented branded UI.

## Visual QA

Verify:

- Asset count and independent files match the visual map.
- Image actually appears in the intended section.
- Correct inline anchoring, readable size, caption adjacency, and Alt text.
- Scene fit: the rendered visual shows the mapped reader/task/setting or product state and supports the section's user need.
- Source and displayed aspect ratios match within 1%; any approved crop is documented and keeps the stated subject visible.
- No crop, stretch, overlap, blank page, or table collision in rendered output.
- Summary and method visuals serve distinct purposes.
