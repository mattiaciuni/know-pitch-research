# Manual Presentations — 40 Real Decks by Payle Domain (Pre-Seed vs Seed)

Each subfolder = Payle correlation domain + stage (pre-seed/seed/series-*). How the deck informs Payle's money layer for AI agents.

| Domain Folder | Stage | Payle Correlation | Decks |
|---|---|---|---|
| `ai-agents_agentic-payments/seed/` | Seed | Payment network where AI agents identify themselves and pay for APIs and information | Skyfire 2024 13p |
| `ai-agents_conversational-ai/seed/` | Seed | Consumer AI agents, conversation | Character.AI 2021 13p |
| `ai-agents_data-ai/pre-seed/` | Pre-Seed | Generative AI infra for enterprise | Seek AI 2023 12p |
| `ai-agents_foundational/seed/` | Seed | Foundational AI infra for agents | OpenAI 2015 13p |
| `ai-agents_gaming/pre-seed/` | Pre-Seed | AI for complex production | Iconic AI 2024 10p |
| `ai-agents_health/pre-seed/` | Pre-Seed | AI for regulated workflows | Crosby Health 2024 8p |
| `ai-agents_infra/pre-seed/` | Pre-Seed | Agentic AI agent-infrastructure layer | Altan 2025 16p, ThriveAI 2025 16p |
| `ai-agents_knowledge/pre-seed/` | Pre-Seed | AI for unstructured company data | Zive 2024 15p |
| `ai-agents_llm-orchestration/seed/` | Seed | LLM orchestration infra for agents | LangChain 2023 12p |
| `ai-agents_networking/pre-seed/` | Pre-Seed | Agent-driven networking/texting | Series 2025 11p |
| `ai-agents_search/seed/` | Seed | AI-native search, challenging incumbent | Perplexity 2023 33p |
| `ai-agents_spending/seed/` | Seed | Centralizes spending limits, budgets and API access across AI providers | Requesty 2025 8p |
| `ai-agents_superintelligence/pre-seed/` | Pre-Seed | AI Agents, AGI positioning | superintelligent 2023 13p |
| `ai-agents_voice-ai/pre-seed/` | Pre-Seed | Voice AI infra, automated dubbing as a SaaS | ElevenLabs 2023 14p |
| `bnpl_credit/seed/` | Seed | EU regulatory navigation | Scalapay 2019 17p, Tabby 2021 9p |
| `bnpl_credit/series-a/` | Series A | BNPL checkout conversion | Afterpay 2015 13p |
| `bnpl_credit/series-b/` | Series B | BNPL infra, FundingFlex model | Klarna 2010 8p |
| `bnpl_credit/series-d/` | Series D | Honest BNPL, transparency | Affirm 2016 13p |
| `category-creation_crypto/seed/` | Seed | Crypto category, YC demo day → investor deck | Coinbase 2012 12p |
| `category-creation_marketplace/pre-seed/` | Pre-Seed | Marketplace category creation | Uber 2008 25p |
| `category-creation_marketplace/seed/` | Seed | Category creation playbook for Payle | Airbnb 2008 11p |
| `devtools_database-infra/seed/` | Seed | Open-source Firebase alternative | Supabase 2020 13p |
| `devtools_database-infra/series-b/` | Series B | DB infra for scale | PlanetScale 2021 13p |
| `devtools_frontend-cloud/seed/` | Seed | DX-first, frontend cloud | Vercel 2020 17p |
| `devtools_issue-tracking/seed/` | Seed | 9-slide brevity benchmark for Payle | Linear 2019 6p |
| `fintech_ai-advice/pre-seed/` | Pre-Seed | Consumer finance recommendations executed by software | Uprise 2022 14p |
| `fintech_card-issuing/seed/` | Seed | Card issuing infra for AI agents | Marqeta 2010 5p |
| `fintech_cards-with-rules/seed/` | Seed | Virtual cards with rules | Privacy.com 2016 9p |
| `fintech_cross-border/pre-seed/` | Pre-Seed | Corporate cards + cross-border accounts with per-entity controls | Kamino 2022 8p |
| `fintech_cross-border/seed/` | Seed | Cross-border infra, transparent pricing | Wise 2011 13p |
| `fintech_invest/pre-seed/` | Pre-Seed | AI-powered investing with automated execution | Pynk 2020 21p |
| `fintech_payments-infra/pre-seed/` | Pre-Seed | Pay-per-use infra | Tiun 2024 10p |
| `fintech_payments-infra/seed/` | Seed | Merchant payments, hardware+software | Square 2009 20p, Stripe 2010 13p |
| `fintech_prepaid-infra/pre-seed/` | Pre-Seed | Prepaid/wallet issuance with employer-funded spend rules | WageFi 2022 10p |
| `fintech_spend-control/seed/` | Seed | Spend management, startup cards | Brex 2017 18p, Ramp 2019 15p |
| `remote-first_kanban/seed/` | Seed | Visual collab, remote workflows | Trello 2011 13p |

**40 real PDFs = all 40 `index.json` entries (40/40), every page an embedded slide image, all pass `verify_pdf()`.**

## Provenance

- BI article decks (`ai-agents_*`, `fintech_ai-advice|cross-border|invest|prepaid-infra`, `fintech_payments-infra/tiun`) were captured as **real slide images** from Business Insider pitch-deck articles and compiled to PDF with `scripts/bi_deck.py` (`capture_method: screenshots`).
- The 9 previously fake ReportLab PDFs (ralio, runtools, stratum, voriq, ishtar, clove, adro, rebloom, finperks) were **deleted and replaced** with verified real decks — see `scripts/replace_flagged_fakes.py`.
- `ai-agents_venue/` was renamed to `ai-agents_networking/` (the real Series deck is a networking agent, not a venue product).
- The 32 synthetic dossiers in `presentations/generated/` were **deleted as fakes** (0 embedded images) — see `presentations/generated/README.md` and `scripts/purge_fake_pdfs.py`.
- Source URLs, verification notes and ≥3 attempted search methods per deck: `index.json:decks[]` (audit via `scripts/audit_methods.py`).
