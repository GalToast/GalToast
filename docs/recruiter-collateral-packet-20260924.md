# Recruiter Collateral Packet — Fred McCullough

**Role:** AI Automation Engineer
**Date:** 2026-09-24
**Links:** [LinkedIn](https://www.linkedin.com/in/fred-mccullough-02981a38a/) · [mccullough.digital](https://mccullough.digital/) · [GitHub](https://github.com/GalToast)

---

## 1. Resume Positioning

### Professional Summary (1 paragraph)

AI Automation Engineer with a track record designing and deploying evidence-driven systems for semantic search, browser automation, and data pipeline orchestration. Built Semantic Explorer — a neighborhood graph search engine over 8,406 public business records — and LeadOps, an AI-assisted lead intelligence pipeline. Skilled in Playwright-driven automation, multi-agent orchestration (Claude/Gemini/Qwen), semantic search and embeddings, and RAG architectures. Combines deep technical execution with a product-minded approach: every system is built to ship, measure, and iterate.

### Proof Bullets

- **Semantic Explorer** — Built a neighborhood graph search system querying 8,406 Montgomery County public business records using semantic embeddings and a custom SQLite pipeline; delivers ranked results via a Leaflet interactive map and Three.js neighborhood graph visualization.
- **LeadOps** — Designed an AI-assisted lead intelligence pipeline (Playwright scraping, embedding store, Claude/Gemini multi-agent classification) that processes unstructured public records into structured lead profiles.
- **CloudScan** — Delivered a free public website audit tool covering performance, security, SEO, and accessibility; demonstrates full-stack deployment and browser automation in production.
- **Browser Automation at Scale** — Runs multi-url Playwright workflows orchestrating concurrent headless browsers across multiple AI models (Claude, Gemini, Qwen) with SQLite state management.
- **Multi-Agent Orchestration** — Architect of agent pipelines that coordinate task decomposition, tool use, and result synthesis across LLMs without reliance on any single vendor.
- **RAG & Semantic Search** — Embeddings-first design across all data products; builds custom vector-adjacent stores using SQLite with distance-ranked retrieval.
- **Operational Decision Support** — Systems engineer for workflows where data is noisy, records are public, and outputs feed human decisions — not black-box automation.

---

## 2. 30-Second Pitch

> "I'm Fred McCullough — I build AI automation systems that turn messy public data into useful products.
>
> Most recently, I built Semantic Explorer: a semantic search engine over 8,406 Montgomery County business records, with an interactive Leaflet map and Three.js neighborhood graph. I also built LeadOps — a multi-agent pipeline that scrapes, embeds, and classifies public lead records using Playwright and Claude/Gemini.
>
> My core stack is semantic search, Playwright automation, multi-agent orchestration, and RAG architectures. I work across the full stack, from data pipeline to deployment.
>
> I'm currently targeting AI Automation Engineer or Applied AI Engineer roles where the work is hands-on, the data is real, and the systems ship."

---

## 3. 2-Minute Walkthrough Script

### Opening (15 sec)
"I'm Fred McCullough. I build AI systems that work with real public data — from scraping and embeddings to multi-agent pipelines that actually ship."

### Semantic Explorer (45 sec)
"Semantic Explorer started as a question: can you do meaningful semantic search over a real-world public dataset without a commercial vector DB?

The dataset is 8,406 Montgomery County public business records. The challenge was getting embeddings for every record, storing them efficiently, and building a query interface that returned relevant results.

I built the pipeline in Python — record collection, embedding generation (using a lightweight embedding model), and storage in SQLite with a custom distance-ranked retrieval layer. For the frontend, I used Leaflet for an interactive map view and Three.js to render a neighborhood graph. The result is a search engine that accepts natural-language queries and returns geographically ranked results. Everything is public and self-hosted — no proprietary vector DB required."

### LeadOps (30 sec)
"LeadOps is an AI-assisted lead intelligence pipeline I built for my own use and then open-sourced. It scrapes public records pages using Playwright, embeds the content, and routes queries through a multi-agent classifier that tags records by category, confidence, and relevance.

The orchestration layer runs Claude, Gemini, and Qwen in parallel for the classification step — so you're not locked into any single model. Results land in a structured SQLite store. The pipeline is designed to be retargeted: swap the scraper, swap the embedding model, swap the classifier."

### CloudScan (15 sec)
"CloudScan is a free public tool — anyone can plug in a URL and get a website audit covering performance, security, SEO, and accessibility. It's a Playwright-based multi-page crawler that runs headless in the browser, collects Lighthouse-equivalent metrics, and formats them into a shareable report. It's a good example of taking browser automation out of the lab and into a product that people actually use."

### Client Context (if asked) (15 sec)
"I work directly with clients on custom automation projects — primarily lead generation, public records aggregation, and operational dashboards. I don't discuss private client specifics publicly, but the common thread across all engagements is taking unstructured public data and turning it into structured, queryable intelligence."

---

## Claim Boundary Reference

When discussing this work, keep to these safe claims:

- **Records count:** 8,406 (public data only)
- **Techniques:** Semantic search / embeddings / Playwright / SQLite / Three.js / Leaflet
- **LeadOps:** Public records pipeline — no private client data
- **Avoid:** Revenue/financial claims, "fully autonomous", private-client specifics
- **Stack keywords:** semantic search, embeddings, Playwright, multi-agent orchestration, RAG, data pipeline engineering, browser automation
