<div align="center">

# DEAICore

**The engineering home of [ReN AI](https://www.myrenx.ai/)**

Data and AI infrastructure for understanding diversity, equity and inclusion as an economic and investment signal.

</div>

---

## What we build

Companies disclose a lot about their people, governance and impact, but it is scattered across annual reports, sustainability reports, proxy statements and regulatory filings, in inconsistent formats. We turn those disclosures into structured, comparable, searchable data, and build AI tools on top of it for investors, analysts and organisations.

### ReN

Our core platform. ReN brings company disclosures, structured DEI and ESG metrics, and AI-assisted research together in one place:

- **Company intelligence**: board and executive demographics, DEI programmes and governance, strategic priorities, policies, and environmental, social and governance data, all linked to the source documents
- **Risk intelligence**: identifies and tracks DEI-related risk across companies and portfolios
- **AI knowledge engine**: retrieval-augmented search and reasoning over a large library of corporate documents, with answers grounded in citations
- **Portfolios and watchlists**: follow the companies you care about and compare them side by side

### DATAx

The data layer behind ReN: a canonical company universe (with ISIN, ticker and CIK identifiers), the document library, and the APIs that serve structured company data to our applications.

### Data pipeline

The engines that keep the data fresh:

- **Ingestion**: collects corporate reports and regulatory filings (including SEC EDGAR, for listed companies and ETFs) into a single document library
- **Classification and extraction**: identifies document types and pulls structured metrics out of unstructured PDFs
- **Indexing**: embeds and indexes documents and their metadata so they can be searched and retrieved by AI

## Tech stack

| Area | Tools |
| --- | --- |
| Backend | Python, FastAPI, SQLAlchemy |
| Data | PostgreSQL, Google Cloud Storage |
| AI | Large language models, embeddings, retrieval-augmented generation, Vertex AI Search |
| Frontend | TypeScript, React, Next.js |
| Infrastructure | Google Cloud (Cloud Run, Cloud SQL, Cloud Scheduler), Firebase Authentication |

## Working here

- Our repositories are private. If you are a team member and cannot see something you need, ask an org admin for access.
- Two-factor authentication is required for all members.
- Work happens on feature branches off `development`; `main` is production.

## Security

If you find a security issue in any of our services, please report it privately to **operations@myrenx.ai** rather than opening a public issue.

---

<div align="center">

[myrenx.ai](https://www.myrenx.ai/)

</div>
