# SEO Article Review Workflow v3.2

GitHub-ready workflow for improving an existing SEO article without destroying its useful content, product-conversion value, evidence, visuals, or publication readiness.

## What changed in v3.2

- Adds a mandatory content-preservation audit before any drafting.
- Treats ordinary "review" and "optimize" requests as **Optimization Mode**, not rewrite requests.
- Replaces single-product logic with product portfolio, placement, and conversion review.
- Defines actual visual-asset delivery, not image plans or placeholders.
- Adds section-level keyword mapping and delivery acceptance gates.
- Blocks final delivery when the output is only an outline, a review memo, an image plan, or an unrendered/unverified artifact.
- Requires scene-relevant, aesthetically intentional visuals and native-aspect-ratio placement, verified on rendered pages.

## Repository map

| File | Purpose |
|---|---|
| `AGENTS.md` | Operating rules and mandatory stage gates. |
| `ARTICLE_REVIEW_SOP.md` | End-to-end article review process. |
| `KEYWORD_OPTIMIZATION_STANDARD.md` | Keyword intent, mapping, and audit rules. |
| `PRODUCT_RECOMMENDATION_STANDARD.md` | Multi-product recommendation, placement, and conversion rules. |
| `standards/CONTENT_PRESERVATION_STANDARD.md` | Protects valuable source content and prevents accidental rewrites. |
| `standards/VISUAL_ASSET_STANDARD.md` | Defines image strategy, asset requirements, and visual QA. |
| `standards/DELIVERY_ACCEPTANCE_STANDARD.md` | Defines publishable deliverables and final QA. |
| `templates/` | Reusable audit and handoff templates. |

## Default operating principle

> Review is not a license to rewrite. Preserve the article's useful information and conversion assets first; remove only duplication, low-value text, and verified inaccuracies; then fill search, keyword, evidence, product, and visual gaps.

## How to use

1. Read `AGENTS.md` and `ARTICLE_REVIEW_SOP.md`.
2. Complete the source asset inventory in `templates/content_asset_audit.md`.
3. Select **Optimization Mode** unless the user explicitly requests a rewrite.
4. Build the keyword and product maps before editing prose.
5. Map the reader/task/setting for every visual, then create or source a scene-relevant asset and record its native ratio.
6. Run every acceptance check in `standards/DELIVERY_ACCEPTANCE_STANDARD.md`.

## Versioning

Use semantic workflow versions. Any change to a hard gate, delivery contract, or asset-preservation rule requires a minor version increase and an entry in `CHANGELOG.md`.
