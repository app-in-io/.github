<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/app-in-io/.github/main/profile/logo.svg" alt="app-in.io" width="80">
  <br>
  app-in.io
  <br>
</h1>

<h3 align="center">AI-Powered Semantic Search API</h3>

<p align="center">
  Search that understands meaning, not just keywords.<br>
  One API call — intelligent results in 100+ languages.
</p>

<p align="center">
  <a href="https://app-in.io">Website</a> ·
  <a href="https://docs.app-in.io">API Docs</a>
</p>

---

### What we build

**app-in.io** is an API-first semantic search service for ecommerce, helpdesk, and content sites.

- **Semantic Search** — understands "comfortable shoes for running" even if your products say "lightweight athletic sneakers"
- **Product Intelligence** — LLM-powered query parsing with intent extraction, price filters, and smart suggestions
- **Helpdesk Mode** — answers questions directly from your docs, PDFs, and site content with cited sources
- **100+ Languages** — multilingual out of the box, no configuration needed

### How it works

```bash
curl -X POST https://api.app-in.io/v1/search/products \
  -H "X-API-Key: sk_live_your_key" \
  -d '{"query": "comfortable running shoes under $100"}'
```

You get back: semantic results with relevance scores, AI-generated summary, and smart clarifying questions — all in one response.

### Security first

Our AI model runs entirely on our infrastructure. Your data is **never sent to third-party AI services**. Complete tenant isolation, private fields, encryption at rest and in transit.

---

<p align="center">
  <sub>Built with semantic vectors, not keyword matching.</sub>
</p>
