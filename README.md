<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=6B21A8&height=200&section=header&text=Hi%20there,%20I'm%20Mahijith%20👋&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=AI%20Engineer%20·%20Platform%20Builder%20·%20ECE%20%5BIIIT%20Trichy%5D&descAlignY=58&descSize=18&descColor=D8B4FE" />

*Building intelligent platforms — from manufacturing infrastructure to data-driven products.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-6B21A8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/v-mahijith-v)
[![Email](https://img.shields.io/badge/Email-Contact-3B0764?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vmahijith@gmail.com)
[![GitHub ALGO-DRAFT](https://img.shields.io/badge/Org-ALGO--DRAFT-0D0D0D?style=for-the-badge&logo=github&logoColor=A855F7)](https://github.com/ALGO-DRAFT)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## ⚙️ Flagship Project — [GigaSouk](https://gigasouk.com)

<div align="center">

**Cloud Factory Infrastructure for India**

*Manufacturing-as-a-Service platform connecting designers, MSME factories, and customers through intelligent routing, escrow payments, and computer-vision quality control.*

[![Live Site](https://img.shields.io/badge/Live-gigasouk.com-6B21A8?style=flat-square&logo=googlechrome&logoColor=white)](https://gigasouk.com)
![Next.js](https://img.shields.io/badge/Next.js_15-0D0D0D?style=flat-square&logo=next.js&logoColor=A855F7)
![FastAPI](https://img.shields.io/badge/FastAPI-3B0764?style=flat-square&logo=fastapi&logoColor=A855F7)
![Supabase](https://img.shields.io/badge/Supabase-3B0764?style=flat-square&logo=supabase&logoColor=A855F7)
![OpenCV](https://img.shields.io/badge/OpenCV-0D0D0D?style=flat-square&logo=opencv&logoColor=A855F7)
![Razorpay](https://img.shields.io/badge/Razorpay_Escrow-6B21A8?style=flat-square&logoColor=white)

</div>

<br>

GigaSouk addresses one of India's largest infrastructure gaps — the disconnect between **63 million MSME manufacturers** and global demand for custom, made-to-order products. Just as AWS virtualized physical servers, GigaSouk virtualizes physical factories: orchestrating designers, manufacturers, and customers on a single platform to fill idle machine capacity.

| Stakeholder | Role |
|---|---|
| 🎨 **Designer** | Uploads CAD, sets royalty terms, and earns passively on every unit sold |
| 🏭 **Manufacturer** | Commits to designs on a jobs board, manufactures on delivery, and gets paid on completion |
| 🛍️ **Customer** | Purchases engineered, made-to-order products at transparent pricing from the nearest committed factory |

> Every product in the shop has a **committed manufacturer** before a customer ever sees it.

<br>

| Dimension | Detail |
|---|---|
| **Market** | $700B+ India MSME manufacturing output · $45B custom / made-to-order segment |
| **Problem** | Factories sit idle while designers cannot reach production; customers pay opaque middleman markups |
| **Solution** | End-to-end MaaS — CAD upload → factory routing → escrow payment → QC gate → doorstep delivery |

<br>

| System | Implementation | Impact |
|---|---|---|
| **AI Routing Engine** | FastAPI · PostGIS · Haversine proximity scoring | Capability and price-commitment filters before proximity sort — stable consumer pricing |
| **QC Gate** | OpenCV geometry (±0.5 mm) + Gemini 2.0 Flash | Automated quality enforcement before any shipment leaves the factory |
| **Escrow Layer** | Razorpay · HMAC-SHA256 webhooks | Funds held until QC passes and delivery is confirmed; auto-split to platform, factory, and designer |
| **Logistics Bridge** | Shiprocket multi-courier API | AWB generated on QC pass; real-time tracking via webhooks |
| **Negotiation Room** | Real-time chat · 24-hour price-lock timer | Designers and manufacturers align on margins before a product goes live |

<details>
<summary><b>Order journey</b></summary>

```
  DESIGNER ──► Upload CAD + set price ──► PLATFORM alerts capable factories
       ◄──── Negotiation Room (24-hr timer) ────► MANUFACTURER commits
  CUSTOMER ◄──── Product LIVE in shop ──────────── committed factory assigned
       ──► Order + Razorpay Escrow ──► Manufacture ──► 5 QC photos ──► OpenCV gate
       ◄── Delivery ◄── Shiprocket AWB ◄── QC pass ──► Royalty + factory payout
```

</details>

<br>

Full-stack engineering, AI/ML pipelines, payments infrastructure, and domain-heavy product design — applied to a platform with measurable economic impact across India's manufacturing ecosystem.

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## 🧠 About Me

I build end-to-end systems that combine **rigorous data analysis** with **production-grade engineering** — from analytics platforms and AI copilots to full-stack marketplaces like GigaSouk.

- 🤖 Integrating **AI and LLMs** into real-world workflows — not demos, deployed products
- 📊 Strong foundations in **statistics, data visualization, and reporting**
- 🛠️ Full ownership across the stack — ingestion, APIs, databases, and user-facing interfaces

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## 🚀 Featured Projects

### 💰 [Revenue Radar — Marketing Attribution + AI Budget Allocation](https://github.com/vmahijith-lgtm/revenue-radar)

> ![dbt](https://img.shields.io/badge/dbt-3B0764?style=flat-square&logo=dbt&logoColor=A855F7) ![DuckDB](https://img.shields.io/badge/DuckDB-0D0D0D?style=flat-square&logoColor=A855F7) ![FastAPI](https://img.shields.io/badge/FastAPI-6B21A8?style=flat-square&logo=fastapi&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-3B0764?style=flat-square&logo=streamlit&logoColor=A855F7) ![Python](https://img.shields.io/badge/Python-0D0D0D?style=flat-square&logo=python&logoColor=A855F7)

End-to-end **multi-touch attribution and AI-powered budget optimization**. Combines dbt data pipelines, DuckDB analytics, Thompson Sampling reinforcement learning, and a real-time Streamlit dashboard.

- ✅ Multi-touch attribution across all marketing channels
- ✅ Thompson Sampling RL for intelligent budget allocation
- ✅ Real-time analytics and performance dashboards
- ✅ Live demo → [revenue-radar.onrender.com](https://revenue-radar.onrender.com)

---

### 🏥 [Clinical Trial Analytics Platform](https://github.com/vmahijith-lgtm/clinical_trial_analytics)

> ![Streamlit](https://img.shields.io/badge/Streamlit-3B0764?style=flat-square&logo=streamlit&logoColor=A855F7) ![Python](https://img.shields.io/badge/Python-0D0D0D?style=flat-square&logo=python&logoColor=A855F7) ![Claude](https://img.shields.io/badge/Anthropic_Claude-6B21A8?style=flat-square&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3B0764?style=flat-square&logo=plotly&logoColor=A855F7)

Production-ready analytics for clinical trial QC data from Excel sources. Processes 23 studies with automated quality scoring, statistical analytics, and a natural-language **"Chat with Data"** interface powered by Claude.

- ✅ Multi-sheet Excel ingestion with memory-optimized processing
- ✅ Automated quality scores and flags across datasets
- ✅ Plain-English AI chat for non-technical stakeholders
- ✅ Export to CSV, Excel, and JSON

---

### 🦉 [Socratic AI Journal](https://github.com/ALGO-DRAFT/Socratic-AI)

> ![Streamlit](https://img.shields.io/badge/Streamlit-3B0764?style=flat-square&logo=streamlit&logoColor=A855F7) ![Whisper](https://img.shields.io/badge/Whisper-0D0D0D?style=flat-square&logo=openai&logoColor=A855F7) ![Ollama](https://img.shields.io/badge/Ollama-6B21A8?style=flat-square&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-3B0764?style=flat-square&logo=sqlite&logoColor=A855F7)

A **100% local, privacy-first** cognitive augmentation app. Users record journal entries by voice; the AI responds with Socratic questions to deepen reflection. Tracks emotional trajectory over time with sentiment analysis.

- ✅ Voice-to-text via OpenAI Whisper — fully offline
- ✅ Llama 3 guided Socratic dialogue via Ollama
- ✅ Emotional trajectory charts per session and across entries
- ✅ Zero external API calls — complete data privacy

---

### 🔬 [AlgoDraft — AI Research Copilot](https://github.com/ALGO-DRAFT/ALGODRAFT)

> ![FastAPI](https://img.shields.io/badge/FastAPI-3B0764?style=flat-square&logo=fastapi&logoColor=A855F7) ![LangChain](https://img.shields.io/badge/LangChain-0D0D0D?style=flat-square&logoColor=A855F7) ![TypeScript](https://img.shields.io/badge/TypeScript-6B21A8?style=flat-square&logo=typescript&logoColor=white) ![VSCode](https://img.shields.io/badge/VS_Code_Extension-3B0764?style=flat-square&logo=visualstudiocode&logoColor=A855F7)

A **VS Code extension and FastAPI backend** that turns research papers into an interactive AI assistant. Ingest PDFs and LaTeX, then chat with your corpus using RAG — local (Ollama) or cloud LLMs.

- ✅ RAG pipeline with ChromaDB vector store and source citations
- ✅ Ollama, OpenAI GPT-4o, Anthropic Claude, Gemini, Hugging Face
- ✅ Live VS Code sidebar with chat, code analysis, and config switching
- ✅ Switch AI providers at runtime without restarting

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-0D0D0D?style=flat-square&logo=python&logoColor=A855F7)
![TypeScript](https://img.shields.io/badge/TypeScript-3B0764?style=flat-square&logo=typescript&logoColor=A855F7)
![SQL](https://img.shields.io/badge/SQL-6B21A8?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-0D0D0D?style=flat-square&logo=r&logoColor=A855F7)

### AI / ML
![LangChain](https://img.shields.io/badge/LangChain-0D0D0D?style=flat-square&logo=langchain&logoColor=A855F7)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-6B21A8?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-3B0764?style=flat-square&logoColor=A855F7)
![Whisper](https://img.shields.io/badge/Whisper-0D0D0D?style=flat-square&logo=openai&logoColor=A855F7)
![OpenCV](https://img.shields.io/badge/OpenCV-6B21A8?style=flat-square&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-3B0764?style=flat-square&logo=scikitlearn&logoColor=A855F7)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0D0D0D?style=flat-square&logoColor=A855F7)

### Data & Analytics
![Pandas](https://img.shields.io/badge/Pandas-0D0D0D?style=flat-square&logo=pandas&logoColor=A855F7)
![NumPy](https://img.shields.io/badge/NumPy-6B21A8?style=flat-square&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3B0764?style=flat-square&logo=plotly&logoColor=A855F7)
![dbt](https://img.shields.io/badge/dbt-0D0D0D?style=flat-square&logo=dbt&logoColor=A855F7)
![DuckDB](https://img.shields.io/badge/DuckDB-6B21A8?style=flat-square&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-3B0764?style=flat-square&logo=scipy&logoColor=A855F7)

### Frameworks & Infrastructure
![Next.js](https://img.shields.io/badge/Next.js-0D0D0D?style=flat-square&logo=next.js&logoColor=A855F7)
![FastAPI](https://img.shields.io/badge/FastAPI-6B21A8?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-3B0764?style=flat-square&logo=streamlit&logoColor=A855F7)
![Supabase](https://img.shields.io/badge/Supabase-0D0D0D?style=flat-square&logo=supabase&logoColor=A855F7)
![Docker](https://img.shields.io/badge/Docker-6B21A8?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-3B0764?style=flat-square&logo=git&logoColor=A855F7)

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## 💡 What Sets Me Apart

| Skill | How I Apply It |
|---|---|
| 🏭 **Platform Engineering** | Built GigaSouk end-to-end — routing, escrow, QC, logistics, and multi-role dashboards |
| 🤖 **AI-Augmented Workflows** | LLMs integrated across exploration, quality control, and user interfaces |
| 📊 **Statistical Rigor** | Applied to clinical, marketing, and research datasets with reproducible pipelines |
| 🛠️ **Full Pipeline Ownership** | Raw ingestion → processing → storage → API → visualization → interface |

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## 🤝 Open to Opportunities

I'm actively looking for roles in:

- 📊 **Data Analytics / Data Engineering**
- 🏭 **Product & Platform Engineering**
- 🤖 **AI / ML Engineering**
- 🔬 **Research & Development (AI-assisted)**

> *"I don't just build tools — I build systems that create real economic impact."*

**Let's connect →** [vmahijith@gmail.com](mailto:vmahijith@gmail.com) · [LinkedIn](https://linkedin.com/in/v-mahijith-v)

<img src="https://capsule-render.vercel.app/api?type=waving&color=6B21A8&height=120&section=footer&fontColor=ffffff" />
