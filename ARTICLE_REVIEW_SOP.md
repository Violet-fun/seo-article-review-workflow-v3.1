# Article Review SOP v3.2

## 0. Delivery Contract and Mode Detection

Before reviewing content, record:

- Required final files and whether the article must be immediately publishable.
- Whether keyword highlighting belongs in a review copy, a publish copy, or both.
- Required image count, asset format, independent image delivery, and visual direction.
- Required product(s), product category, conversion purpose, CTA, internal links, or evidence requirements.
- Optimization Mode or Rewrite Mode.

If the user asks for optimization/review, select Optimization Mode. Do not proceed to a full rewrite without explicit authorization.

## 1. Content Preservation Audit (mandatory before editing)

Create an inventory using `templates/content_asset_audit.md`.

Evaluate every substantial source asset:

- Search-answer modules: introduction, Quick Answer, decision guidance, FAQ, Verdict.
- Decision assets: tables, comparison matrices, checklists, workflows, scenarios.
- Authority assets: data, source citations, expert boundaries, verified claims.
- Conversion assets: product explanations, product workflows, use cases, benefits, limitations, CTAs.
- Visual assets: original images, diagrams, captions, Alt text, product screens.

Assign one action only: **Keep**, **Merge**, **Refine**, **Relocate**, **Replace with an equivalent**, or **Delete**.

Deletion is permitted only for true repetition, empty generality, unsupported claims, stale facts, or content with no search, decision, evidence, or conversion value. State the reason and preserve an equivalent asset where required.

## 2. Topic, Intent, and User Journey Review

Identify:

- Primary search intent and secondary intents.
- User scenarios, urgency, pain points, and decision needs.
- Source states or problem states that require different routes.
- The minimum answer a skimming reader needs before deeper detail.

Build the article as a user journey. Example pattern:

`Diagnose state -> Choose solution category -> Follow method -> Validate outcome -> Preserve/share -> FAQ/CTA`

## 3. Structure Review

Check:

- One H1 only.
- A Quick Answer that actually resolves the first decision.
- One structural dimension per heading level.
- Parallel grammar at the same heading level.
- Related solutions grouped under a common category instead of duplicated as flat, competing sections.
- A consistent method pattern such as: `Best for -> Why it fits -> Steps -> What to check -> Product/CTA -> Limits`.

Do not keep two sections separate merely because they use different tools if they solve the same stage of the same user journey. Create one category, then distinguish tools/scenarios underneath it.

## 4. Solution Logic Review

Classify each solution before drafting:

1. **Required/source-level solution**: fixes the source state or enables later work.
2. **Direct solution**: solves the reader's central problem at that decision point.
3. **Alternative solution**: solves the same problem in a materially different scenario.
4. **Adjacent solution**: supports a related workflow step.
5. **Boundary-sensitive solution**: useful only after limitations and risks are clear.

Every solution must include a concise `Best for` block with three concrete, recognizable scenarios or long-tail situations. Include one or two boundary cases when relevant.

## 5. Product Portfolio, Placement & Conversion Review

Use `PRODUCT_RECOMMENDATION_STANDARD.md` and `templates/product_portfolio_map.md`.

For each product, verify role, problem fit, placement, evidence, differentiated value, limit, alternative, and CTA. A product should appear only where the reader has enough context to understand why it is recommended.

Keep direct-solution conversion content strong: scenario-specific value, practical workflow, comparison/selection aid, constraints, and a next action. Fact-checking should improve claims, not erase persuasive utility.

## 6. Keyword Review

Use `KEYWORD_OPTIMIZATION_STANDARD.md` and `templates/keyword_map.md`.

Map each keyword to search intent, article section, target count, and natural sentence. Audit distribution by section, not only by whole-document totals.

## 7. Visual Asset Review and Production

Use `standards/VISUAL_ASSET_STANDARD.md` and `templates/visual_asset_map.md`.

Plan actual visuals before final composition. Every main content section needs a visual role: problem identification, workflow, scenario comparison, method operation, product experience, or outcome/archiving.

Preserve effective original visuals. New visuals should complement a missing task, not replace useful assets merely for stylistic uniformity.

For every new visual, map the real reader, task, and setting or product state first. Produce a credible scene or recognizable workflow that answers that section's need; do not use a white-background text card, generic arrow diagram, or repeated composition as a substitute. Record source dimensions and the intended native ratio in the visual map. When embedding, size proportionally and never inherit an incompatible legacy image frame. A crop needs a documented reason and must retain the mapped subject.

## 8. EEAT and Evidence Review

Check that claims are proportionate and sourced where needed.

- Retain useful existing evidence, case material, technical boundaries, and authority references.
- Use current primary or official sources for version-sensitive product claims.
- Mark illustrative workflows as examples, not claimed customer outcomes.
- Add sources where a reader needs a factual basis to choose a solution.

## 9. Edit and Regress

Implement approved actions from the source asset audit. After editing, compare the revised article to the source:

- Effective word-count change and explanation for material reduction.
- Preserved/replaced tables, cases, workflows, FAQ, evidence, visuals, and product modules.
- No accidental loss of decision depth or product conversion logic.

If source effective-information retention drops below 70%, stop and require an explicit rewrite decision. A lower threshold may be used only when the user expressly requests a short version.

## 10. Final QA and Delivery

Run the complete checklist in `standards/DELIVERY_ACCEPTANCE_STANDARD.md`.

Render the final document to images and inspect every page containing a visual. For each asset, verify scene fit, source/display ratio within 1%, visible subject, caption adjacency, and absence of clipping, stretching, overlap, or collision. If rendering cannot be performed, label the package **Structurally verified - visual QA pending**; it is not publish-ready.

Do not label an output “final” or “publish-ready” if it is an outline, a review memo, a visual plan, a document with placeholders, or an artifact that has not passed the available visual/layout checks.
