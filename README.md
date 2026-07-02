<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=6B21A8&height=200&section=header&text=Hi%20there,%20I'm%20Mahijith%20👋&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=Data%20Analyst%20·%20AI%20Engineer%20·%20ECE%20%5BIIIT%20Trichy%5D&descAlignY=58&descSize=18&descColor=D8B4FE" />

*Building intelligent systems that turn complex data into clear decisions.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-6B21A8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/v-mahijith-v)
[![Email](https://img.shields.io/badge/Email-Contact-3B0764?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vmahijith@gmail.com)
[![GitHub ALGO-DRAFT](https://img.shields.io/badge/Org-ALGO--DRAFT-0D0D0D?style=for-the-badge&logo=github&logoColor=A855F7)](https://github.com/ALGO-DRAFT)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## ⚙️ Flagship Project — [GigaSouk](https://github.com/vmahijith-lgtm/Gigasouk)

<div align="center">

**Cloud Factory Infrastructure for India**

*AI-powered Manufacturing-as-a-Service — connecting designers, MSME factories, and customers through intelligent routing, escrow payments, and computer-vision quality control.*

[![Next.js](https://img.shields.io/badge/Next.js_15-0D0D0D?style=flat-square&logo=next.js&logoColor=A855F7)](https://nextjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-3B0764?style=flat-square&logo=fastapi&logoColor=A855F7)](https://fastapi.tiangolo.com/)
[![Supabase](https://img.shields.io/badge/Supabase_Postgres_+_Auth-6B21A8?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com/)
[![OpenCV](https://img.shields.io/badge/OpenCV_QC-0D0D0D?style=flat-square&logo=opencv&logoColor=A855F7)](https://opencv.org/)
[![Razorpay](https://img.shields.io/badge/Razorpay_Escrow-3B0764?style=flat-square&logoColor=A855F7)](https://razorpay.com/)

</div>

**GigaSouk is the project I'm building to solve one of India's largest infrastructure gaps** — the disconnect between 63 million MSME manufacturers and the global demand for custom, made-to-order products. Just as AWS virtualised physical servers, GigaSouk virtualises physical factories: filling idle machine capacity by orchestrating designers, factories, and customers on a single platform.

| Stakeholder | Role |
|---|---|
| 🎨 **Designer** | Uploads a CAD file, sets a royalty %, and earns passively on every unit sold |
| 🏭 **Manufacturer** | Browses a jobs board, commits to designs that suit their margins, and gets paid on delivery |
| 🛍️ **Customer** | Buys engineered, made-to-order products at a transparent price — manufactured by the nearest committed factory |

> Every product visible in the shop already has a **committed manufacturer** before the customer ever sees it.

### Why this matters

| Dimension | Detail |
|---|---|
| **Market** | $700B+ India MSME manufacturing output · $45B custom/made-to-order segment |
| **Problem** | Factories sit idle while designers can't reach production; customers pay opaque middleman markups |
| **Solution** | End-to-end MaaS — from CAD upload → factory routing → escrow payment → QC gate → doorstep delivery |

### What I built

| System | Implementation | Impact |
|---|---|---|
| **AI Routing Engine** | FastAPI + PostGIS · Haversine proximity · capability + price-commitment filters | Stable consumer prices; nearest capable factory assigned automatically |
| **QC Gate** | Hybrid OpenCV (±0.5mm geometry) + Gemini 2.0 Flash (visual defects) | Automated quality enforcement before any shipment leaves the factory |
| **Escrow Layer** | Razorpay + HMAC-SHA256 webhooks | Funds locked until QC passes and delivery confirmed; auto-split to platform, factory, and designer |
| **Logistics Bridge** | Shiprocket multi-courier API | AWB auto-generated on QC pass; real-time order tracking via webhooks |
| **Negotiation Room** | Real-time chat + 24-hr price-lock timer | Designers and manufacturers agree on margins before a product goes live |

```
  DESIGNER ──► Upload CAD + set price ──► PLATFORM alerts capable factories
       ◄──── Negotiation Room (24-hr timer) ────► MANUFACTURER commits
  CUSTOMER ◄──── Product LIVE in shop ──────────── committed factory assigned
       ──► Order + Razorpay Escrow ──► Manufacture ──► 5 QC photos ──► OpenCV gate
       ◄── Delivery ◄── Shiprocket AWB ◄── QC pass ──► Royalty + factory payout
```

This is where my skills converge — **full-stack engineering, AI/ML pipelines, payments infrastructure, and domain-heavy product design** — applied to a platform with real economic impact for India's manufacturing ecosystem.

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## 🧠 About Me

I specialize in transforming raw, complex datasets into actionable insights with **AI-powered tooling**. I bring together strong analytical skills with hands-on development experience to build end-to-end solutions that actually get used.

- 🤖 Proficient at **integrating AI/LLMs effectively** into real-world workflows
- 📊 Strong foundations in **statistics, data visualization, and reporting**
- 🛠️ Full-stack mindset — from data pipelines to interactive web dashboards

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## 🚀 Featured Projects

### 🏥 [Clinical Trial Analytics Platform](https://github.com/vmahijith-lgtm/clinical_trial_analytics)
> ![Streamlit](https://img.shields.io/badge/Streamlit-3B0764?style=flat-square&logo=streamlit&logoColor=A855F7) ![Python](https://img.shields.io/badge/Python-0D0D0D?style=flat-square&logo=python&logoColor=A855F7) ![Claude](https://img.shields.io/badge/Anthropic_Claude-6B21A8?style=flat-square&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3B0764?style=flat-square&logo=plotly&logoColor=A855F7)

A production-ready analytics platform for processing and analyzing clinical trial QC data from Excel sources. Processes 23 studies with automated quality scoring, statistical analytics, and a natural-language **"Chat with Data"** interface powered by Claude AI.

- ✅ Ingests multi-sheet Excel files with memory-optimized processing
- ✅ Auto-generates quality scores and flags across datasets
- ✅ AI chat lets non-technical stakeholders query data in plain English
- ✅ Exports results to CSV, Excel, and JSON

---

### 🦉 [Socratic AI Journal](https://github.com/ALGO-DRAFT/Socratic-AI)
> ![Streamlit](https://img.shields.io/badge/Streamlit-3B0764?style=flat-square&logo=streamlit&logoColor=A855F7) ![Whisper](https://img.shields.io/badge/Whisper-0D0D0D?style=flat-square&logo=openai&logoColor=A855F7) ![Ollama](https://img.shields.io/badge/Ollama-6B21A8?style=flat-square&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-3B0764?style=flat-square&logo=sqlite&logoColor=A855F7)

A **100% local, privacy-first** cognitive augmentation app. Users record journal entries by voice, and the AI responds with Socratic questions — helping them think deeper, not just get answers. Tracks emotional trajectory over time with sentiment analysis.

- ✅ Voice-to-text via OpenAI Whisper (runs fully offline)
- ✅ Llama3 guided Socratic dialogue via Ollama
- ✅ Emotional trajectory charts per session and across entries
- ✅ Zero external API calls — complete data privacy

---

### 🔬 [AlgoDraft — AI Research Copilot](https://github.com/ALGO-DRAFT/ALGODRAFT)
> ![FastAPI](https://img.shields.io/badge/FastAPI-3B0764?style=flat-square&logo=fastapi&logoColor=A855F7) ![LangChain](https://img.shields.io/badge/LangChain-0D0D0D?style=flat-square&logoColor=A855F7) ![TypeScript](https://img.shields.io/badge/TypeScript-6B21A8?style=flat-square&logo=typescript&logoColor=white) ![VSCode](https://img.shields.io/badge/VS_Code_Extension-3B0764?style=flat-square&logo=visualstudiocode&logoColor=A855F7)

A **VS Code extension + FastAPI backend** that turns your research papers into an interactive AI assistant. Ingest PDFs and LaTeX papers, then chat with your research corpus using RAG — works with local (Ollama) or cloud LLMs.

- ✅ RAG pipeline with ChromaDB vector store and source citations
- ✅ Supports Ollama, OpenAI GPT-4o, Anthropic Claude, Gemini, Hugging Face
- ✅ Live VS Code sidebar with chat, code analysis, and config switching
- ✅ Switch AI providers at runtime without restarting

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-0D0D0D?style=flat-square&logo=python&logoColor=A855F7)
![SQL](https://img.shields.io/badge/SQL-3B0764?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-6B21A8?style=flat-square&logo=r&logoColor=white)

### AI / ML
![LangChain](https://img.shields.io/badge/LangChain-0D0D0D?style=flat-square&logo=langchain&logoColor=A855F7)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-6B21A8?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-3B0764?style=flat-square&logoColor=A855F7)
![Whisper](https://img.shields.io/badge/Whisper-0D0D0D?style=flat-square&logo=openai&logoColor=A855F7)
![scikit-learn](https://img.shields.io/badge/scikit--learn-6B21A8?style=flat-square&logo=scikitlearn&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-3B0764?style=flat-square&logoColor=A855F7)

### Data & Analytics
![Pandas](https://img.shields.io/badge/Pandas-0D0D0D?style=flat-square&logo=pandas&logoColor=A855F7)
![NumPy](https://img.shields.io/badge/NumPy-6B21A8?style=flat-square&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3B0764?style=flat-square&logo=plotly&logoColor=A855F7)
![SciPy](https://img.shields.io/badge/SciPy-0D0D0D?style=flat-square&logo=scipy&logoColor=A855F7)

### Frameworks & Tools
![Streamlit](https://img.shields.io/badge/Streamlit-6B21A8?style=flat-square&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-3B0764?style=flat-square&logo=fastapi&logoColor=A855F7)
![SQLite](https://img.shields.io/badge/SQLite-0D0D0D?style=flat-square&logo=sqlite&logoColor=A855F7)
![Git](https://img.shields.io/badge/Git-6B21A8?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-3B0764?style=flat-square&logo=docker&logoColor=A855F7)

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## 💡 What Sets Me Apart

| Skill | How I Apply It |
|-------|---------------|
| 🤖 **AI-Augmented Workflows** | Integrate LLMs into every phase — exploration, QC, UI — cutting time-to-insight dramatically |
| 📊 **R & Statistical Analysis** | Rigorous statistical thinking for clinical and research datasets |
| 🗄️ **SQL & Database Design** | Schema design, CRUD, and query optimization (SQLite, PostgreSQL) |
| 🛠️ **Full Pipeline Ownership** | Raw ingestion → processing → storage → visualization → interface |

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />


</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=6B21A8&height=2" />

## 🤝 Open to Opportunities

I'm actively looking for roles in:
- 📊 **Data Analytics / Data Engineering**
- 🏥 **Informatics**
- 🤖 **AI/ML Engineering**
- 🔬 **Research & Development (AI-assisted)**

> 💬 *"I don't just build tools — I build tools that make people smarter."*

**Let's connect →** [vmahijith@gmail.com](mailto:vmahijith@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=6B21A8&height=120&section=footer&fontColor=ffffff" />
