# 👋 Hi, I'm Jack Ng

Finance director turned technical founder. After 10+ years in Hong Kong capital markets — M&A advisory, debt restructuring, and audit at KPMG — I'm now pursuing a Master of Information Technology (AI specialisation) at the University of Western Australia and building AI-powered tools full-time under [The Capitalyst Limited](https://thecapitalyst.com).

My work sits at the intersection of financial domain knowledge and modern AI. I believe systematic intelligence — regulatory, market, or content — should be accessible without a Bloomberg terminal or a team of analysts.

---

## 🚀 What I'm Building

### [Masthead](https://cap-auto-smc.web.app/landing) — Live · Commercialised
Multi-tenant LinkedIn content automation platform for professional services firms. Runs an autonomous pipeline: discovers relevant industry news (Tavily), classifies and scores articles against brand content pillars (Z.AI / GLM models), and generates ready-to-publish LinkedIn posts, weekly articles, and monthly intelligence briefs — all in the brand's voice. Includes drag-and-drop content calendar, PDF carousel generation, scheduled LinkedIn publishing via official OAuth API, and full Stripe billing.

**Stack:** React 19 + TypeScript + Firebase (Firestore, Cloud Functions, Hosting) + Z.AI (GLM-4.5-air / GLM-5) + Tavily + LinkedIn OAuth

**Traction:** Live enterprise client (trust company, AUA $180M+ USD). Pricing $29–$199/mo.

---

### [MER Intelligence System](https://github.com/jack-cap/mer-intel) — Active Development · Private
Personal origination tool for identifying restructuring, RTO, and dual-listing opportunities in ASX-listed small-cap mining, energy & resources companies. Runs fully headless on a Synology NAS.

Ingests the full ASX-listed universe (~905 GICS Materials/Energy companies) via the public markitdigital JSON API, processes quarterly cashflow reports (4C/5B) to compute cash runway and distress signals, scores every company on a Distress × Fit matrix, selects a top-50 Watchlist for deep-crawl and LLM extraction, and enriches with ASIC register data and Tavily web intelligence.

Built to solve a specific problem: arriving in Perth in June 2026 with no local network in WA resources, and needing to show up to every coffee chat knowing more about a company than the person across the table.

**Stack:** Python 3.12 + FastAPI + Celery + Redis + PostgreSQL 18 + MinIO + DeepSeek v4-pro/flash + Tavily  
**Tests:** 256 passing (pytest + Hypothesis, including property-based correctness suite)

---

### [The Capitalyst Brief](https://github.com/jack-cap/capitalyst-brief) — Running Weekly
Automated weekly intelligence report on 10 major PE/alternatives firms (Blackstone, KKR, Apollo, Ares, Oaktree, Bridgewater, GMO, and others). Aggregates SEC EDGAR filings, Tavily IR searches, and 7-day news, runs per-firm deep analysis via DeepSeek, synthesises into a 9-section markdown report, and delivers as a styled HTML email every Sunday. Runs on GitHub Actions at zero ongoing cost.

**Stack:** Python + FastAPI + DeepSeek v4-pro/flash + Tavily + SMTP  
**Output:** 5 issues published to date, covering FS KKR distress, Bridgewater's gold thesis, GMO's Japan rotation, and the rate-hike repricing across May 2026.

---

### [Money In & Out](https://jack-cap.github.io/MoneyInOut-Page/) — Live · App Store
Native iOS/macOS expense tracker. On-device AI receipt scanner (no cloud processing), iCloud sync across all Apple devices, visual spending analysis. Privacy-first: receipts and transactions never leave your devices.

**Stack:** Swift + SwiftUI + Core ML + CloudKit  
**Traction:** 128+ App Store downloads since launch (free).

---

## ⏸️ On Hold

**Auto Manager** — Open-source, local-first AI bookkeeper. Automates receipt processing and double-entry accounting for Manager.io using a multi-agent supervisor architecture (LangGraph). Deferred while MER Intelligence takes priority.

**AtomDoc** — Transform PDFs into queryable knowledge bases with hierarchical structure and AI-powered navigation. Deferred.

**PearlGate** — AI-powered corporate intelligence platform for Hong Kong's capital markets. Deferred.

**Contayo** — Contact intelligence system for meeting debriefs. Deferred.

---

## 🛠️ How I Build

**Languages:** Python, Swift, TypeScript  
**LLM & AI tooling:** LangChain, LangGraph, DeepSeek API, Z.AI (GLM models), Tavily, Ollama  
**Infrastructure:** Firebase (Firestore, Cloud Functions, Auth, Hosting), FastAPI, Celery, Redis, PostgreSQL, MinIO  
**AI-assisted development:** I work extensively with Claude, Kiro, and Gemini as coding collaborators. This is a core part of my workflow, not a shortcut — it lets me ship things I couldn't build alone and learn faster than any other method I've found.

I'm a domain expert first, builder second. The AI handles syntax I haven't memorised; I handle the product decisions and financial logic that require a decade of context.

---

## 💼 Background

- **Corporate Finance Advisory** — Director, Oriental Patron Asia Limited (HK), 10 years. Type 6 Responsible Officer (Advising on Corporate Finance). M&A, debt restructuring, RTOs, dual-listings. Deal values >HK$1B.
- **Audit** — Assistant Manager, KPMG Hong Kong (2014–2016). IPO and annual audit, Main Board and GEM.
- **CPA** — Member, Hong Kong Institute of Certified Public Accountants (2018–)
- **CFA** — Passed Levels 1 & 2. Level 3 candidate.
- **Education** — MIT(AI), University of Western Australia (2026) · BCom (Accounting), University of Melbourne (2011-2013), WAM 79.6

---

## 📍 Currently

Perth, WA — building the MER Intelligence System, starting UWA in July 2026, and looking for opportunities in WA resources restructuring and cross-border (HK/China ↔ Australia) corporate finance.

---

## 📫 Connect

- LinkedIn: [linkedin.com/in/jacng](https://linkedin.com/in/jacng)
- Email: jack@thecapitalyst.com
- Web: [thecapitalyst.com](https://thecapitalyst.com)
