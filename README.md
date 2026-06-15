# Hi, I'm Raf

24-year-old final-year BSc Computer Science graduate at Bournemouth University, **Achieved a first**.  
Aspiring **Software Engineer / Full‑Stack Engineer** (London / South UK), focused on building reliable web apps, APIs, cloud deployments and ML/LLM-powered features.

---

### Snapshot

- 🎓 BSc Computer Science, Bournemouth University – final year, **predicted First**  
  - 95/100 in Deep Learning unit  
  - 70/100 (First) in Computability & Complexity unit
- 💻 Interests: full-stack SaaS apps, CI/CD, cloud-native, applied deep learning / LLMs, optimisation, **AI Agents**  
- 🌍 Location: London / hybrid across South of the UK  
- 🎯 Actively looking for **graduate Software Engineer / Full‑Stack Engineer roles in the UK**
- ⚙️ Built full-stack applications, delivered to clients and solved real-world problems

---

### Tech stack

**Core:** Python, JavaScript, TypeScript, HTML, CSS

**Frontend:** React, Tailwind 4.0, Shadcn, Lucide

**Backend & APIs:** FastAPI, RESTful API design, OpenAI API (LLM integration)  

**Cloud & DevOps:** Google Cloud (App Engine, Cloud Run, Cloud SQL, Secret Manager, Cloud Functions), Docker, Git & GitHub CI/CD, Digital Ocean App Platform

**Databases:** PostgreSQL (Neon, Cloud SQL), MongoDB Atlas (NoSQL), Qdrant (Vector Database)

**Data, ML & Optimisation:** CNNs, LLMs, AI Agents, deep learning, Kaggle, NumPy, genetic algorithms, metaheuristics, greedy heuristics, Matplotlib, Pytorch, OpenAI API

---

### Featured projects

#### AI Legal Contract Reviewer – GPT/RAG Contract Analysis + Clause Risk Explainer

Full-stack **legal AI contract reviewer** for analysing English-law contract PDFs, classifying contract segments, extracting clauses, and generating **plain-English clause explanations** with client-facing risk analysis using **GPT 5.4**, **RAG**, and a lawyer-reviewed workflow.

* Built a two-phase legal AI system combining an end-to-end ML research pipeline with a deployed full-stack web application
* Compared **zero-shot GPT 5.4 mini**, **GPT 5.4 mini + RAG**, and **fine-tuned Legal-BERT** on a lawyer-annotated dataset of **3,548 contract segments**
* Classifies contract text into seven structural categories including clauses, definitions, headings, recitals, preamble/parties and other sections
* Uses **Azure Document Intelligence** to scan uploaded PDFs and extract structured contract segments
* Uses **OpenAI embeddings** and **Qdrant vector search** to retrieve relevant context from the same contract before explaining clauses
* Generates plain-English clause explanations with dedicated **Client Risk** analysis, reviewed by legal annotators
* Includes secure login with **Supabase Auth**, PDF upload/storage with **DigitalOcean Spaces**, and in-browser PDF viewing with clause highlighting
* **CI/CD:** GitHub repository connects directly to **DigitalOcean App Platform** → pushes trigger automatic frontend/backend build and deployment
* **Tech:** Python, TypeScript, FastAPI, React 19, Vite, Tailwind CSS, Supabase Auth, Azure Document Intelligence, OpenAI, GPT 5.4 mini, GPT 5.4, RAG, Qdrant, DigitalOcean Spaces, DigitalOcean App Platform, PyTorch, Hugging Face Transformers, sentence-transformers, pandas, NumPy, Matplotlib, Label Studio, Git, GitHub
* **Live demo:** Available [HERE](https://contract-reviewer-xyae8.ondigitalocean.app/)

---

#### MnA CRM – Deal & Relationship Management + LLM Email Assistant

Full‑stack **M&A CRM** for managing deal pipelines, organisations, contacts and notes, with an integrated **OpenAI GPT 5‑nano chatbot** for drafting emails, and a production-style CI/CD pipeline.

- Deal, contact and notes management with clear UX and robust backend design  
- LLM-powered chatbot drafts outreach and follow‑up emails to leads (disabled in public demo)  
- **CI/CD:** develop in VS Code → commit to GitHub → Docker builds image → deploy container to **Google Cloud Run** (managed HTTPS endpoint)  
- Originally deployed on **Google App Engine** with PostgreSQL on **Cloud SQL**  
- Uses broader GCP services including **Cloud Functions**, **Secret Manager**, and external DBs (**MongoDB**, **Neon PostgreSQL**)  
- **Tech:** Python, JavaScript, HTML, CSS, REST APIs, OpenAI, Docker, GitHub, Google Cloud Run, App Engine, Cloud Functions, Cloud SQL, MongoDB, Neon PostgreSQL  
- **Live demo:** Available [HERE](https://mna-crm-ai-610840296940.europe-west1.run.app/login)

---

#### Deep Learning Footprint Classifier

Deep learning project built with **pytorch** to classify footprint images in a single, well-documented **Google Colab notebook**, achieving **95/100** in the Deep Learning unit.

- End‑to‑end pipeline: data loading, preprocessing, model training, evaluation and visualisation  
- Convolutional neural network built with **pytorch** for **binary image classification**  
- Achieved **0.81 validation accuracy** on the private Kaggle competition (good generalisation)  
- Clear experiment tracking, metrics and design justification; notebook is fully reproducible and reviewable  
- **Tech:** Python, deep learning (CNNs), pytorch, pandas, Google Colab, Kaggle, model evaluation & experimentation
- **Full Machine Learning notebook:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/raf945/Deep_learning_Footprint_classifer/blob/main/Deep_learning_footprint_classifier.ipynb).

---

#### Flexible Job Shop Scheduling – Genetic Metaheuristic

Python-based **genetic metaheuristic** to find near-optimal solutions to the **Flexible Job Shop Problem (FJSP)**.

- Models jobs, operations and machines with flexible routing  
- Implements **random, greedy and genetic** scheduling algorithms  
- Evaluates and compares approaches (e.g. makespan, utilisation) using **Matplotlib**  
- Built with **NumPy** for efficient schedule/population representation and manipulation  
- Achieved **70/100 (First)** in the Computability & Complexity unit  
- **Tech:** Python, NumPy, genetic algorithms, metaheuristics, greedy heuristics, scheduling & optimisation, Matplotlib

---

#### LLM Chatbot – Live Web Application

LLM-powered chatbot deployed as a real user-facing product and integrated into a client website.

- Backend calls **OpenAI APIs** for natural language queries and responses  
- Application deployed via **Render.com**  
- Chat interface embedded into a **WordPress** site using a custom script for a seamless UX  
- Successfully deployed for a client; **public demo:** https://www.superioroutreach.ai/  
- **Tech:** Python, JavaScript, HTML, CSS, OpenAI API, Render.com, WordPress embedding

---

### How I like to work

- Write **clean, readable code** with clear project structure  
- Comfortable working end‑to‑end: data models, APIs, front‑end integration, deployment  
- Experienced with **cloud services, containers, CI/CD pipelines and optimisation algorithms**  
- Learn by building and iterating on real projects and coursework

---

### Get in touch

- LinkedIn: https://www.linkedin.com/in/raf-christian-82024b242/
