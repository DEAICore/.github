<div align="center">

# ReN AI

**The engineering home of ReN AI**

Building advanced AI infrastructure, data pipelines, and agentic workflows for public equity research, filings forensics, and portfolio risk intelligence.

</div>

---

## What we build

Public companies disclose vital information regarding their governance, risks, and strategic priorities across annual reports, proxy statements, and complex regulatory filings. We turn those unstructured disclosures into standardized, comparable data and build sophisticated AI automation tools on top of it for institutional investors, analysts, and organizations.

## Core platforms

### ReN AER

*Automated public equity and ETF research and filings forensics.*

- **Company intelligence:** deep forensics on public equities, linking strategic priorities, governance, and financials directly to source documents.
- **Watchlists & comparisons:** follow the companies you care about and seamlessly compare their filings and data side by side.

### ReN PRIE

*Portfolio risk intelligence engine.*

- **Qualitative risk profiling:** generates comprehensive risk profiling and scoring on public equities.
- **Automated risk tracking:** automatically tracks 8 distinct dimensions of risk across portfolios, instantly identifying exposure shifts and emerging threats.

### ReN Agent Workforce

Underpinning both platforms is our proprietary workforce of AI agents designed to handle complex, multi-step workflow automation. To maximize execution efficiency and aggressively reduce hallucinations, this workforce is powered by our bespoke **Domain-Specific Language Model (DSLM)** and **custom knowledge graphs**.

These agents autonomously drive deep analytical tasks in the background and power our interactive chat interface, **Ask ReN**, ensuring all outputs are precise, context-aware, and grounded in structural data.

## Enterprise integration

To support enterprise users scaling our capabilities within their own environments, we are actively developing robust **APIs** and **Model Context Protocol (MCP)** integrations. This allows institutions to securely embed our proprietary data layers, risk engines, and agent workforce directly into their existing internal systems.

## Data pipeline

The engines that keep our financial and corporate data fresh:

- **Ingestion engine:** collects corporate reports and regulatory filings (including SEC EDGAR, for listed companies and ETFs) into a single document library.
- **Classification and extraction engine:** identifies document types and pulls structured metrics out of unstructured PDFs.
- **Indexing & graphing:** embeds, indexes, and maps documents and their metadata into our custom knowledge graphs so they can be retrieved by our DSLM and agents.

## Tech stack

| Area | Tools |
| --- | --- |
| Backend | Python, FastAPI, SQLAlchemy |
| Data | PostgreSQL, Google Cloud Storage, custom knowledge graphs |
| AI | DSLM, large language models, embeddings, RAG, Vertex AI Search, MCP |
| Frontend | TypeScript, React, Next.js |
| Infrastructure | Google Cloud (Cloud Run, Cloud SQL, Cloud Scheduler), Firebase Auth |

## Working here

- Our repositories are private. If you are a team member and cannot see something you need, ask an org admin for access.
- Two-factor authentication is required for all members.
- Work happens on feature branches off `development`; `main` is production.

## Security

If you find a security issue in any of our services, please report it privately to **[operations@myrenx.ai](mailto:operations@myrenx.ai)** rather than opening a public issue.

---

<div align="center">

[myrenx.ai](https://myrenx.ai)

</div>
