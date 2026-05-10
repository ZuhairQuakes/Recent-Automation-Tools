# AI Automation Portfolio

Three recently developed production AI tools are built to solve real business workflow problems.
Each tool was designed, built, and deployed solo, from problem identification through to working software.

---

## Tools

### 1. Groblox Event Activation — Quote Generator
**The problem:** Generating a client quote for a branded event activation took 4–8 hours of manual work per client — reading a brief, calculating module requirements, looking up pricing, and writing a proposal from scratch. During major events like the Australian Grand Prix, a team handled 5–10 brand activations simultaneously.

**What it does:** A brand client fills in a 2-minute briefing form. The tool sends the brief to the Claude API, which generates a fully structured, itemised activation proposal in under 30 seconds — ready to download as a branded PDF and send directly to the client.

**Impact:** Reduced quote generation from 4–8 hours to 30 seconds. Eliminated pricing inconsistency across the team.

**Demo:** [Watch demo](https://docs.google.com/videos/d/1XI1T_TxL71WeSD24mde30cHyr538MVYXv6FkUw7OTvU/edit?usp=sharing)

**Stack:** Python, Flask, Claude API (Anthropic), HTML/CSS/JavaScript, PDF generation

---

### 2. Internal Document Q&A Assistant
**The problem:** Staff spent 30–45 minutes searching through years of internal records — spreadsheets, PDFs, scanned receipts, policy documents — to answer a single question. Knowledge was trapped in files and in people's heads.

**What it does:** Staff type a question in plain English. The tool searches across all internal documents using a RAG (Retrieval-Augmented Generation) pipeline and returns a verified, sourced answer in seconds — citing exactly which document the information came from.

**Impact:** Query resolution reduced from 30–45 minutes to approximately 10 seconds — a 100x speedup. Adopted immediately with no training required.

**Demo:** [Watch demo](https://docs.google.com/videos/d/1tnJAY1oPBnsGLALkoYzlgfXq0cVdRttBtjOPGphcBzI/edit?usp=sharing)

**Stack:** Python, Flask, Claude API (Anthropic), LangGraph, FAISS vector store, HuggingFace sentence embeddings, Docker

---

### 3. Fleet Availability Dashboard
**The problem:** When a customer called asking whether a specific hire unit was available, the sales team had to call the yard, check a spreadsheet, or ask around — slow, unreliable, and occasionally wrong.

**What it does:** A live internal dashboard showing the real-time status of 40 hire units across Victoria, NSW and Queensland — availability, current client, site location, weekly rate, and upcoming returns in the next 30 days. Fully filterable by status, unit type, and state. Click any unit to see full details and hire history.

**Impact:** Sales team can answer customer availability questions in under 3 seconds while still on the phone — no callbacks, no manual checking.

**Demo:** [Watch demo](https://docs.google.com/videos/d/1ygZxhiQQC4hMxKq55w33Obw9Nf81EHfGM-9bNhMfkyQ/edit?usp=sharing)

**Stack:** Python, Flask, JavaScript, Chart.js, HTML/CSS

---

## How Each Tool Was Built

All three tools follow the same process:

1. **Problem first** — identified a specific manual workflow costing real time or money
2. **Simplest solution** — chose the right tool for the job, not the most complex one
3. **Built solo** — design, back-end, front-end, and deployment handled by one person
4. **Tested with real users** — validated against the actual workflow before considering it done
5. **Documented** — every tool includes setup instructions and a working demo

---

## Tech Used Across Projects

| Category | Tools |
|---|---|
| AI and LLMs | Claude API (Anthropic), LangGraph, HuggingFace |
| Back-End | Python, Flask, FastAPI |
| Front-End | JavaScript, HTML5, CSS3, Chart.js |
| RAG and Search | FAISS vector store, sentence-transformers |
| Deployment | Docker, CI/CD |
| Automation | n8n, Make.com, Zapier |

---

## Contact

**Mohd Zuhair, PhD**
Melbourne, VIC, Australia
zuhair.alig31@gmail.com
[LinkedIn](https://www.linkedin.com/in/quakes/) | [Google Scholar](https://scholar.google.com/citations?hl=en&user=NHRsjgEAAAAJ&view_op=list_works&sortby=pubdate)
