 # Xdata – Historical Social Media Intelligence Platform

**Search the past. Understand the context. Verify the evidence.**

Xdata is an AI-powered historical social media intelligence platform designed to help individuals, journalists, and researchers investigate public social media statements over time.

Initially focused on **X (formerly Twitter)**, Xdata aims to retrieve historical public posts, organise them chronologically, discover topic-related discussions, identify changing narratives, and generate evidence-based insights.

## 🎯 Vision

Transform historical social media content into organised, searchable, and verifiable research.

Xdata will help users understand:
- What a public account has said about a particular issue.
- How statements and positions have evolved over time.
- Which themes and arguments repeatedly appear.
- How public narratives change across different periods.
- What original evidence supports an AI-generated finding.

## 🚀 Core Features (Planned)

- Public X account verification.
- Historical post retrieval using the official X API.
- User-defined topics and date ranges.
- Chronological post organisation.
- English, Urdu, and Roman Urdu research support.
- AI-assisted topic discovery and semantic search.
- Evidence-linked summaries and historical comparisons.
- Downloadable research reports.

## 🗺️ Development Roadmap

### Phase 1 – Historical Data Collection
- Python-based local application.
- Official X API integration.
- Public account verification.
- Historical post retrieval and pagination.
- Date and author validation.
- Local JSON data export.

### Phase 2 – AI-Powered Research Engine
- Topic-based filtering.
- Multilingual text processing.
- Semantic search and embeddings.
- Historical theme identification.
- AI-assisted summaries.
- Evidence-based statement comparisons.

### Phase 3 – Web Application
- Interactive research dashboard.
- Searchable historical timelines.
- Investigation management.
- Evidence inspection.
- Research report generation.
- Future expansion to other authorised social media platforms.

## 🛠️ Proposed Technology Stack

| Component | Technology |
|---|---|
| Programming language | Python |
| API communication | Requests |
| Data source | Official X API |
| Initial storage | JSON |
| Backend | FastAPI |
| Frontend | React, TypeScript, Vite |
| AI services | Gemini and Groq |
| Embeddings | Sentence Transformers |
| Database | PostgreSQL |
| Vector search | pgvector |
| Orchestration | LangGraph (if required) |
| Deployment | Vercel + Python backend hosting |

*Technologies will be introduced gradually as the project develops.*

## 🔍 Research Principles

Xdata follows an evidence-first research approach:

1. Original posts remain the primary evidence.
2. AI-generated interpretations remain separate from original content.
3. Important findings must link to their supporting posts.
4. Retrieval limitations and missing data must be disclosed.
5. Translations and summaries must be clearly identified.
6. Research should not produce unsupported judgements about individuals.

## 🔐 Privacy and Responsible Use

- Use publicly available content through authorised APIs.
- Respect platform terms, rate limits, and access restrictions.
- Never access private messages or protected content without lawful authorisation.
- Protect API credentials and user data.
- Maintain transparency about data collection and analytical limitations.

## 📌 Current Project Status

**Development Stage:** Phase 1 – Local Proof of Concept Preparation

The immediate objective is to establish a reliable historical data retrieval workflow using Python and the official X API.

X API access, Full-Archive Search eligibility, and current pricing are yet to be verified.

No paid retrieval or production deployment has been authorised.

## 🌍 Initial Target Market

Pakistan, with potential international expansion after validating the initial product.

## 💡 Long-Term Goal

Build a reliable historical social intelligence research platform that makes public digital discourse easier to investigate, understand, compare, and verify.

---

**Project:** Xdata  
**Category:** AI / Social Media Intelligence / Historical Research  
**Initial Platform:** X (formerly Twitter)  
**License:** To be decided  
**Status:** Early Development
