# Hi there, I'm Alan Liang! 👋
### 🚀 Software Engineer | Python Developer | ML/DL Learner

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect_with_me-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/alan-liang-958817226)
[![Email](https://img.shields.io/badge/Email-Contact_me-c14438?style=flat&logo=gmail)](mailto:alanliang0428@gmail.com)
[![Kaggle](https://img.shields.io/badge/Kaggle-alanlinag-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/alanlinag)

> Used to spend my days optimizing ad campaigns. Got tired of the spreadsheets,
> picked up Python, and never looked back. These days I'm deep into LLMs and RAG —
> building things from scratch is still my favorite way to actually understand how they work.

---

## 👨‍💻 About Me

Python developer who came from the data side of things — 
spent years in ad-tech staring at numbers, and eventually decided 
I'd rather be the one building the tools. 
Now I work on AI applications, mostly around LLMs and RAG pipelines.

* Currently building: **MarTech RAG Generator** — an end-to-end RAG pipeline 
  that helps marketers generate content using their own data
* Going deep on: **ML/DL fundamentals** — how transformers actually work, 
  what embeddings really represent, and why my vector search keeps returning garbage
* I think good code should be: readable first, correct second, fast third — 
  in that order

---

## 🛠️ Technical Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | Python |
| **AI / RAG** | LlamaIndex, ChromaDB, Gemini API (LLM + Embedding), RAG Pipeline Design |
| **Backend** | FastAPI, Celery, REST API |
| **DevOps & Cloud** | Docker, GitHub Actions CI/CD, GCP Cloud Run, Artifact Registry |
| **Concepts** | OOP, Clean Code, System Design, Async Task Queue |

---

## 🏆 Featured Projects

### 1. [MarTech RAG Generator](https://github.com/Alanliang666/MarTech-RAG-Generator)
> *FastAPI · LlamaIndex · ChromaDB · Gemini · Celery · Docker · GCP Cloud Run*

A production-ready RAG microservice that lets marketers stop writing ad copy from scratch.
Feed it your past campaigns, ask for new copy — it pulls the relevant context and generates 
5 variations using Gemini 2.5 Flash.

* Built an async task queue with **Celery** so heavy LLM calls don't block the API
* Containerized with **Docker** and deployed to **GCP Cloud Run** via GitHub Actions CI/CD
* Used **LlamaIndex + ChromaDB** for vector storage and similarity search on historical ad data

### 2. [Argos Poly — Polymarket Arbitrage Scanner](https://github.com/Alanliang666/argos-poly)
> *asyncio · WebSocket · REST API · Real-time Data Pipeline*

A real-time arbitrage scanner for prediction markets. Built around one design principle:
eliminate unnecessary waiting at every layer of the pipeline.

* Used **asyncio + WebSocket** to subscribe to live order book streams concurrently —
  synchronous polling would've missed opportunities that close in seconds
* Debugged a silent data issue: tracked it down to the REST API returning closed markets 
  with no active order book, fixed with an upstream filter at ingestion

### 3. [Computer Vision From Scratch](https://github.com/Alanliang666/cv-from-scratch-python)
> *Pure Python · No OpenCV · Pixel-level Algorithm Implementation*

Built image processing algorithms from scratch using only raw pixel RGB data — no cv2, no shortcuts.
The point wasn't just to get the effect. It was to understand why it works.

* Implemented ghost removal using **Euclidean distance in RGB space** to pick the most 
  "average" pixel across multiple shots — the same math behind k-means and nearest-neighbor search
* Built fire detection using per-pixel brightness ratios — threshold-based classification 
  without any ML model

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-brown-six-50.vercel.app/api?username=alanliang666&show_icons=true&theme=buefy&hide_border=true&hide_title=true&count_private=true&v=1" height="150" alt="My GitHub Stats" />
  <img src="https://github-readme-stats-brown-six-50.vercel.app/api/top-langs/?username=alanliang666&layout=compact&theme=buefy&hide_border=true&hide_title=true&v=1" height="150" alt="Top Languages" />
</div>

---

## ⭐ Leetcode stats

![LeetCode Stats](https://leetcard.jacoblin.cool/Alanliang666)

---

_Thanks for stopping by! I'm always looking to connect, so feel free to check out my projects and reach out if you want to chat about code or AI._
