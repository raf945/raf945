# FDE && Full-Stack

24-year-old Forward Deployed Engineer at **Superior Outreach AI**. I build AI agents, automations and full-stack apps, and take them from design to production with real clients.

---

### Snapshot

- 🎓 BSc (Hons) Computer Science, Bournemouth University: **First-Class Honours** (2026)
  - 95/100 in Deep Learning and 95/100 in Software Engineering
- 💼 Forward Deployed Engineer at Superior Outreach AI (Jul 2025 to present)
- 🤖 Focus: **AI agents**, agentic workflows (LangGraph, n8n), RAG, full-stack SaaS apps, cloud deployment
- 🌍 Location: London / hybrid across the South of the UK
- 🎯 Open to **Forward Deployed Engineer, Full-Stack Engineer and AI Engineer roles in the UK**

---

### Experience

**Forward Deployed Engineer** | Superior Outreach AI | Jul 2025 to present

- Design, build and deploy AI agents, internal automations and client software
- Develop and maintain the company platform, backend APIs and cloud infrastructure
- Built AI agents that automate content for the company's inbound marketing
- Build agentic workflows in **LangGraph** and **n8n** that automate internal processes and connect business systems
- Build and refine AI calling agents that hold live conversations with prospects
- Work directly with clients and own delivery end to end: requirements, design, deployment and iteration

**Full-Stack Engineer (Contract)** | Frontpace | Feb 2026 to Jul 2026

- Built a data-collection and form app from scratch with **FastAPI** and JavaScript, used by executive and management teams
- Set up and ran a **Debian** VPS with Python, nginx and systemd
- Integrated **Microsoft Azure** for secure, automated email delivery

---

### Tech stack

**Languages:** Python, TypeScript, JavaScript, SQL, HTML, CSS

**AI & Agents:** LLMs, AI agents, RAG, LangGraph, LangChain, OpenAI API, n8n, Qdrant (vector DB), LLM evaluation

**Frontend:** React, Vite, Tailwind CSS, shadcn/ui, Lucide

**Backend & APIs:** FastAPI, RESTful API design, Supabase (Auth, Postgres)

**Cloud & DevOps:** Google Cloud (Cloud Run, App Engine, Cloud SQL, Secret Manager, Cloud Functions), Microsoft Azure, AWS, DigitalOcean (App Platform, Spaces), Docker, GitHub CI/CD, Debian Linux, nginx, systemd

**Databases:** PostgreSQL (Neon, Cloud SQL, Supabase), MongoDB Atlas, Qdrant

**ML & Optimisation:** PyTorch, CNNs, Hugging Face Transformers, NumPy, pandas, Matplotlib, Kaggle, genetic algorithms, metaheuristics

**Testing & Tools:** pytest, Git, Claude Code, Codex, Cursor

---

### Featured projects

#### Inbound Marketing Content Agents (Superior Outreach)

Full-stack inbound marketing tool that runs **AI agents for content generation**, built for Superior Outreach's own marketing.

- Agents research trending topics and draft content
- Each draft is checked against its source URLs, then passes a quality check before publishing
- Agents learn from performance data and improve their output over time
- **Tech:** Python, FastAPI, LangGraph, LangChain, OpenAI, React, TypeScript, Supabase, Azure

---

#### AI Legal Contract Reviewer: GPT/RAG Contract Analysis + Clause Risk Explainer

Full-stack **legal AI contract reviewer** for English-law contract PDFs. It classifies contract segments, extracts clauses and writes **plain-English clause explanations** with client-facing risk analysis, using **GPT 5.4**, **RAG** and a lawyer-reviewed workflow.

- Built a two-phase legal AI system: an end-to-end ML research pipeline plus a deployed full-stack web app
- Compared **zero-shot GPT 5.4 mini**, **GPT 5.4 mini + RAG** and **fine-tuned Legal-BERT** on a lawyer-annotated dataset of **3,548 contract segments**
- Classifies contract text into seven structural categories, including clauses, definitions, headings, recitals, preamble/parties and other sections
- Uses **Azure Document Intelligence** to scan uploaded PDFs and extract structured segments
- Uses **OpenAI embeddings** and **Qdrant vector search** to pull relevant context from the same contract before explaining clauses
- Generates plain-English explanations with a dedicated **Client Risk** analysis, reviewed by legal annotators
- Secure login with **Supabase Auth**, PDF storage on **DigitalOcean Spaces**, and in-browser PDF viewing with clause highlighting
- **CI/CD:** pushes to GitHub trigger automatic frontend and backend builds on **DigitalOcean App Platform**
- **Tech:** Python, TypeScript, FastAPI, React 19, Vite, Tailwind CSS, Supabase Auth, Azure Document Intelligence, OpenAI, GPT 5.4 mini, GPT 5.4, RAG, Qdrant, DigitalOcean Spaces, DigitalOcean App Platform, PyTorch, Hugging Face Transformers, sentence-transformers, pandas, NumPy, Matplotlib, Label Studio, Git, GitHub

---

#### M&A CRM: Deal & Relationship Management + LLM Email Assistant

Full-stack **M&A CRM** for deal pipelines, organisations, contacts and notes, with an **OpenAI GPT 5-nano chatbot** for drafting emails and a production-style CI/CD pipeline.

- Deal, contact and notes management with a clean UX and solid backend design
- LLM chatbot drafts outreach and follow-up emails to leads (disabled in the public demo)
- **CI/CD:** commit to GitHub → Docker builds the image → container deploys to **Google Cloud Run** (managed HTTPS endpoint)
- Originally deployed on **Google App Engine** with PostgreSQL on **Cloud SQL**
- Also uses **Cloud Functions**, **Secret Manager**, **MongoDB** and **Neon PostgreSQL**
- **Tech:** Python, JavaScript, HTML, CSS, REST APIs, OpenAI, Docker, GitHub, Google Cloud Run, App Engine, Cloud Functions, Cloud SQL, MongoDB, Neon PostgreSQL
- **Live demo:** [mna-crm-ai on Cloud Run](https://mna-crm-ai-610840296940.europe-west1.run.app/login)

---

#### Deep Learning Footprint Classifier

**PyTorch** CNN that classifies footprint images, built in a single, well-documented **Google Colab notebook**. Part of the Deep Learning unit, where I scored **95/100**.

- End-to-end pipeline: data loading, preprocessing, training, evaluation and visualisation
- Convolutional neural network for **binary image classification**
- Reached **0.81 validation accuracy** in a private Kaggle competition
- Clear experiment tracking, metrics and design justification; the notebook is fully reproducible
- **Tech:** Python, PyTorch, CNNs, pandas, Google Colab, Kaggle
- **Notebook:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/raf945/Deep_learning_Footprint_classifer/blob/main/Deep_learning_footprint_classifier.ipynb)

---

#### Flexible Job Shop Scheduling: Genetic Metaheuristic

Python **genetic metaheuristic** that finds near-optimal solutions to the **Flexible Job Shop Problem (FJSP)**.

- Models jobs, operations and machines with flexible routing
- Implements **random, greedy and genetic** scheduling algorithms
- Compares approaches on makespan and utilisation with **Matplotlib**
- Uses **NumPy** for efficient schedule and population handling
- Scored **70/100 (First)** in the Computability & Complexity unit
- **Tech:** Python, NumPy, genetic algorithms, metaheuristics, greedy heuristics, Matplotlib

---

#### LLM Chatbot: Live Web Application

LLM chatbot deployed as a real user-facing product on a client website.

- Backend calls **OpenAI APIs** to answer natural-language questions
- Deployed on **Render.com**
- Chat interface embedded into a **WordPress** site with a custom script
- Live for a client: **public demo** at [superioroutreach.ai](https://www.superioroutreach.ai/)
- **Tech:** Python, JavaScript, HTML, CSS, OpenAI API, Render.com, WordPress

---

### How I like to work

- Work directly with clients and turn real-world feedback into fixes and features
- Write **clean, readable code** with a clear project structure
- Work end to end: data models, APIs, frontend, deployment and iteration after launch
- Use AI coding tools (Claude Code, Codex, Cursor) to ship faster, and hand-code where a problem needs a new approach
- Learn by building and shipping real projects

---

### Get in touch

- Email: rafael@prchristensen.com
- LinkedIn: https://www.linkedin.com/in/raf-christian-82024b242/
