# SEMPITE

**Digital consulting for small businesses & personal brands — from New York.**

We close the gap between *"I know my digital presence is behind"* and *"I can't afford an agency that actually pays attention to me."* Two pillars:

- **AI Search Visibility** — helping brands get found in Google *and* AI search (ChatGPT, Perplexity, Gemini, Google AI Overviews). Industry-aware brand audits, GEO/AEO strategy, and ongoing visibility tracking.
- **eCommerce Operations** — tooling and consulting born from 9+ years running multi-marketplace operations (Shopify, Amazon, eBay) at scale.

Everything runs on our own stack: proprietary crawlers, AI-search trackers, and audit engines on privately hosted LLMs — client data never leaves our infrastructure.

## AI Search Visibility API

Check whether AI engines know a brand — live, across five engines — with one call:

```bash
curl -X POST https://sempite.com/api/v1/visibility/check \
  -H "Authorization: Bearer sk_live_..." \
  -H "Content-Type: application/json" \
  -d '{"brand": "Your Brand", "domain": "yourbrand.com"}'
```

Returns per-engine presence, whether your site is cited, and a 0–100 visibility score. Free tier: 10 checks/month, no card required.

- 📖 [API docs](https://sempite.com/api/v1/docs)
- 🐍 Python client: [`sempite-python`](https://github.com/SEMPITEHQ/sempite-python)
- 🔑 [Get a free key](https://sempite.com/ai-search-visibility-api/)

## Elsewhere

[sempite.com](https://sempite.com) · [Free visibility check](https://sempite.com/free-check) · [AI Visibility Index (monthly research)](https://sempite.com/research/ai-visibility-index/) · [Blog](https://sempite.com/blog/) · [LinkedIn](https://www.linkedin.com/company/112611169)
