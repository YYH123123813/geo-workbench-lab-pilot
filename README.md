# GEO Workbench Lab Pilot

GEO Workbench Lab is a self-owned public pilot for testing a claim-safe GEO workflow: crawl a page, extract its content, audit its page-quality signals, collect AI answer evidence, map prompt failures to page gaps, prepare a reviewed optimization patch, publish changes, and retest.

Live page: https://yyh123123813.github.io/geo-workbench-lab-pilot/

Repository: https://github.com/YYH123123813/geo-workbench-lab-pilot

## What GEO Workbench Lab is

GEO Workbench Lab is a public test project for studying whether a page is prepared for AI search visibility evidence collection. It focuses on controllable signals:

- crawlability
- extractability
- answerability
- prompt-to-page gap mapping
- claim-safe page patching
- structured source content
- llms.txt documentation
- before/after retesting

It does not guarantee AI ranking, mentions, recommendations, or citations.

## What this pilot tested

This pilot tested whether a weak public page could be transformed into a stronger source-like page and whether that page-quality improvement would translate into immediate ChatGPT visibility lift.

The workflow covered:

1. before page publication;
2. public URL validation;
3. before crawl, extraction, and audit;
4. 12 manually collected ChatGPT baseline answers;
5. prompt-to-page gap mapping;
6. claim-safe optimization patch generation;
7. local patch application and validation;
8. GitHub Pages publication;
9. after crawl, extraction, and audit;
10. 12-prompt ChatGPT after-test;
11. before/after metric comparison;
12. external discoverability diagnosis.

## Public and local review URLs

Current published assets:

- Live optimized page: https://yyh123123813.github.io/geo-workbench-lab-pilot/
- Before snapshot: https://yyh123123813.github.io/geo-workbench-lab-pilot/before.html
- llms.txt: https://yyh123123813.github.io/geo-workbench-lab-pilot/llms.txt

Supporting pages added locally in the source-cluster phase:

- Methodology: ./methodology.html
- Docs: ./docs.html
- Comparison: ./comparison.html
- Examples: ./examples.html
- Changelog: ./changelog.html

Expected public URLs after a future publish step:

- Methodology: https://yyh123123813.github.io/geo-workbench-lab-pilot/methodology.html
- Docs: https://yyh123123813.github.io/geo-workbench-lab-pilot/docs.html
- Comparison: https://yyh123123813.github.io/geo-workbench-lab-pilot/comparison.html
- Examples: https://yyh123123813.github.io/geo-workbench-lab-pilot/examples.html
- Changelog: https://yyh123123813.github.io/geo-workbench-lab-pilot/changelog.html

This local phase does not push or publish those supporting pages.

## What improved

The page-quality layer improved:

| Signal | Before | After |
|---|---:|---:|
| Page audit score | 60 | 95 |
| Schema JSON-LD blocks | 0 | 1 |
| llms.txt status | 404 | 200 |
| FAQ item count | 3 | 7 |
| Table count | 0 | 2 |
| H2 count | 4 | 14 |

The after page is public, crawlable, canonicalized, and structured with visible FAQ and comparison tables.

## What did not improve

The immediate ChatGPT after-test did not observe natural AI lift:

| Metric | Before | After |
|---|---:|---:|
| mention_rate | 0.0833 | 0.0833 |
| recommendation_rate | 0.0833 | 0.0833 |
| citation_rate | 0.0 | 0.0 |
| target_url_accuracy_rate | 0.0 | 0.0 |
| competitor_above_us_rate | 0.9167 | 0.9167 |

The after-test was ChatGPT-only, manually pasted, screenshot-missing, and model-unknown. It is useful directional evidence, not full enterprise-grade proof.

## Current interpretation

The current bottleneck appears to be external discoverability and entity evidence rather than landing-page quality. ChatGPT can read the target URL when the URL is supplied, but it does not naturally surface GEO Workbench Lab in generic discovery and recommendation prompts.

## Evidence folder concept

The pilot keeps evidence in a structured local folder:

```text
self-owned-real-pilot-001/
  04-baseline-ai-answers/
  06-crawl-before/
  07-extraction-before/
  08-audit-before/
  10-prompt-gap-map/
  11-optimization-patch/
  12-technical-pack/
  14-local-apply-validation/
  15-publication/
  16-crawl-after/
  17-extraction-after/
  18-audit-after/
  19-before-after-compare/
  20-ai-after-test/
  24-final-reports/
  25-external-discoverability/
```

The evidence folder makes the workflow auditable and helps separate page-quality claims from AI-lift claims.

## Repository structure

```text
geo-workbench-lab-pilot/
  index.html          # optimized public page
  before.html         # preserved weak before snapshot
  llms.txt            # advisory AI-readable summary
  sitemap.xml         # crawl discovery file
  robots.txt          # crawl permission file
  assets/style.css    # local CSS
  pilot-materials/    # prompt pack and baseline materials
```

Supporting assets added locally:

```text
methodology.html
docs.html
comparison.html
examples.html
changelog.html
```

## How to run a similar self-owned pilot

1. Create a weak but crawlable public page.
2. Validate URL, robots, sitemap, and noindex state.
3. Run before crawl, extraction, and page-quality audit.
4. Collect a fixed prompt baseline from AI systems.
5. Save raw answer text, screenshots, platform, model, timestamp, and exact prompt.
6. Map prompt failures to missing page sections and evidence gaps.
7. Generate a claim-safe patch package.
8. Apply and publish only after review.
9. Run after crawl, extraction, and audit.
10. Retest the same prompts.
11. Report page-quality lift separately from AI answer lift.

## Limitations

- This pilot is self-owned; it is not a customer case study.
- It does not prove ChatGPT ranking improvement.
- It does not prove citation improvement.
- It does not prove multi-platform visibility lift.
- It provides no multi-platform proof.
- It does not claim formal security or compliance status or sensitive-data suitability.
- It does not claim production deployment status or enterprise deployment readiness.

## No ranking guarantee

GEO Workbench Lab does not guarantee that ChatGPT, Perplexity, Gemini, Google AI Overviews, or any other AI system will mention, recommend, rank, or cite a page. It helps test and improve controllable evidence signals, then measures what actually happens.
