# SEMPITE

**Digital consulting for small businesses and personal brands, from New York.**

We close the gap between *"I know my digital presence is behind"* and *"I can't afford an agency that actually pays attention to me."* Two pillars:

- **AI Search Visibility** for personal brands and small businesses: getting found in Google *and* in AI answers (ChatGPT, Perplexity, Gemini, Claude, Google AI Overviews). Industry-aware brand audits for actors, musicians, artists and local businesses, GEO/AEO strategy, and ongoing visibility tracking.
- **eCommerce Operations**: tooling and consulting from years of running multi-marketplace operations (Shopify, Amazon, eBay) at scale.

Everything runs on our own stack: crawlers, AI-search trackers and audit engines on privately hosted LLMs, so client data never leaves our infrastructure.

## Open source

| Repo | What it does |
|---|---|
| [`llms-txt-kit`](https://github.com/SEMPITEHQ/llms-txt-kit) | Generate and validate `llms.txt` files. Zero-dependency CLI and Python library; build one from your sitemap in a single command. `pip install llms-txt-kit` |
| [`sempite-python`](https://github.com/SEMPITEHQ/sempite-python) | Python client for the AI Search Visibility API. |

## AI Search Visibility API

Check whether AI engines know a brand, live, across five engines, with one call:

```bash
curl -X POST https://sempite.com/api/v1/visibility/check \
  -H "Authorization: Bearer sk_live_..." \
  -H "Content-Type: application/json" \
  -d '{"brand": "Your Brand", "domain": "yourbrand.com"}'
```

Returns per-engine presence, whether your site is cited, and a 0 to 100 visibility score. Free tier: 10 checks a month, no card required. [API docs](https://sempite.com/api/v1/docs) · [Get a free key](https://sempite.com/ai-search-visibility-api/)

## Free tools

- [Site audit](https://sempite.com/tools/site-audit): crawlability, on-page, speed, structured data and AI readiness
- [AI visibility check](https://sempite.com/free-visibility-check/): does ChatGPT, Perplexity, Gemini or Google AI know your brand?
- [AI readiness score](https://sempite.com/tools/ai-readiness-score) ([methodology](https://sempite.com/tools/ai-readiness-score/methodology)) · [AI citation checker](https://sempite.com/tools/ai-citation-checker)
- [llms.txt generator](https://sempite.com/tools/llms-txt-generator) · [Google rank checker](https://sempite.com/tools/google-rank-checker) · [What page of Google am I on?](https://sempite.com/tools/what-page-of-google-am-i-on)
- [All tools](https://sempite.com/tools/)

## Research

Original studies on AI search and the web, published with open methodology: [AI Visibility Index (monthly)](https://sempite.com/research/ai-visibility-index/) · [llms.txt vs AI citations](https://sempite.com/research/llms-txt-vs-ai-citations/) · [llms.txt audit](https://sempite.com/research/llms-txt-audit/) · [All research](https://sempite.com/research/)

## Elsewhere

[sempite.com](https://sempite.com) · [Brand Audit](https://sempite.com/website-audit/) · [Blog](https://sempite.com/blog/) · [LinkedIn](https://www.linkedin.com/company/112611169)
