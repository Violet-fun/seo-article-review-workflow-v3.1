# Workflow Bootstrap — Required Before Every Article Review

This file is the mandatory entry point for **SEO Article Review Workflow v3.7.0**. A request to use this workflow is authorization to execute this bootstrap; the user does not need to restate the rules in every task.

## 1. Read before editing

Read these files, in order, before opening or changing article prose:

1. `README.md` and `CHANGELOG.md`
2. `AGENTS.md` and `ARTICLE_REVIEW_SOP.md`
3. `PRODUCT_RECOMMENDATION_STANDARD.md` and `KEYWORD_OPTIMIZATION_STANDARD.md`
4. `standards/CONTENT_PRESERVATION_STANDARD.md`, `standards/VISUAL_ASSET_STANDARD.md`, and `standards/DELIVERY_ACCEPTANCE_STANDARD.md`
5. The relevant templates: `delivery_contract.md`, `content_asset_audit.md`, `serp_structure_evidence.md`, `product_portfolio_map.md`, `keyword_map.md`, `visual_asset_map.md`, `release_evidence.json`, `final_human_qa.md`, and `gate_ledger.md`

Record this bootstrap in `workflow_bootstrap` within release evidence before editing. Preflight will reject a release without it.

## 2. Inputs the user must provide

- Source article DOCX
- Keyword XLSX

The following are required only when not already declared in the repository's project-level policy: a core conversion product, audience/locale, output language, compliance limitation, or an approved exception. Do not invent a product policy; record `none` when no product is designated.

## 3. Fixed execution contract

Run Optimization Mode by default. Preserve useful source information, do not produce an outline or shrinkage draft, derive structure from current SERP/intent rather than a reference outline, perform content-economy review, map natural keyword roles, supply required visuals for every H2, and run preflight plus final human QA.

For a named core conversion product, first verify the exact task against a current official feature page:

- `direct_supported`: use a direct product solution; never use Ultra Tips.
- `adjacent_authorized_route`: use the complete boundary-sensitive Ultra Tips route.
- `no_truthful_route`: block release pending an approved alternative.

Do not call a release final or publish-ready until all gates pass. If page rendering is unavailable, use only `Structurally verified - visual QA pending`.

## 4. Minimal user instruction

After attaching the DOCX and XLSX, the user only needs to send:

```text
请使用 SEO Article Review Workflow v3.7.0 对附件文章进行完整回审，默认采用 Optimization Mode，保留原文有效信息，不得改写成提纲或缩水稿。
```
