<!-- ═══════════════════════════════  HEADER  ═══════════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,55:1e3a5f,100:7dd3fc&height=200&section=header&text=Meet%20Acharya&fontSize=62&fontColor=e0f2fe&fontAlignY=40&animation=twinkling" alt="Meet Acharya" width="100%" />
</p>

<p align="center">
  <img src="./meet-acharya.png" alt="Photo of Meet Acharya" width="190" />
</p>

<h3 align="center">AI/ML Engineer &nbsp;·&nbsp; Full Stack Developer</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to%20Work-Full--time%20%C2%B7%20Freelance%20%C2%B7%20Internships%20%C2%B7%20OSS-7dd3fc?style=for-the-badge&labelColor=0f172a" alt="Open to work" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=MeetAcharya24&label=PROFILE%20VIEWS&color=7dd3fc&style=flat-square" alt="Profile views" />
  <a href="https://github.com/MeetAcharya24?tab=followers">
    <img src="https://img.shields.io/github/followers/MeetAcharya24?label=FOLLOWERS&style=flat-square&color=7dd3fc&labelColor=0f172a&logo=github&logoColor=7dd3fc" alt="GitHub followers" />
  </a>
</p>

<br/>

## `~/whoami`

```typescript
const meetAcharya = {
  title: ["AI/ML Engineer", "Full Stack Developer"],
  focus: "Generative AI, LLMs & RAG",
  mission: "Building intelligent applications, AI agents & real-world solutions",

  stack: {
    languages:  ["Python"],
    ai:         ["LangChain", "Google ADK", "Gemini", "scikit-learn", "ElevenLabs (STT/TTS)"],
    frontend:   ["React", "Next.js"],
    backend:    ["FastAPI", "Flask", "SQLite", "Neo4j"],
    exploring:  ["Agentic AI", "NLP", "Machine Learning", "Cloud Technologies"],
  },

  launchedProjects: [
    "TATA Motors AI ChatBot — voice + avatar truck assistant on Google ADK & Gemini",
    "Acharya Hospital — AI-powered hospital management with disease prediction",
    "GraphRAG — multi-hop Q&A over a Neo4j knowledge graph with Gemini",
  ],

  certifications: [
    "Microsoft Certified: Power BI Data Analyst Associate — Microsoft, 2025",
    "ITS: Data Analytics — Certiport, 2025",
    "Python for Data Science, AI and Development — IBM, 2024",
    "Introduction to Software Engineering — IBM, 2024",
  ],

  status: "Currently interning — still open to new opportunities",
  openTo: ["Full-time", "Freelance", "Internships", "Open-source collabs"],
};
```

<br/>

## Featured Projects

### 01 &nbsp;/&nbsp; TATA Motors AI ChatBot

An information-only AI assistant for TATA Motors commercial vehicles. It lists and compares trucks, recommends the right one for your goods, distance and terrain, and estimates trip time and transport cost in INR. You can type, talk hands-free, or chat with a lip-synced avatar, and guardrails refuse anything off-topic.

<p align="center">
  <a href="https://github.com/MeetAcharya24/TATA-Motors">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=MeetAcharya24&repo=TATA-Motors&theme=nord&title_color=7dd3fc&icon_color=7dd3fc&text_color=7dd3fc&border_color=7dd3fc" alt="TATA-Motors repo card" />
  </a>
</p>

| Layer | Technology |
|:--|:--|
| Agent framework | Google Agent Development Kit (ADK) |
| LLM | Gemini |
| Voice | ElevenLabs speech-to-text & text-to-speech, browser VAD, barge-in |
| Interface | Custom web app: avatar, chat and voice over WebSocket, streaming replies |
| Safety | Instruction guardrails + `before_model_callback` off-topic filter |
| Language | Python |

**Code →** [github.com/MeetAcharya24/TATA-Motors](https://github.com/MeetAcharya24/TATA-Motors)

<br/>

### 02 &nbsp;/&nbsp; Acharya Hospital — Management System

An AI-powered hospital management system that brings patient records, doctors and appointments together in one place. It adds machine-learning disease prediction, a built-in chatbot and healthcare analytics.

<p align="center">
  <a href="https://github.com/MeetAcharya24/Acharya-Hospital">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=MeetAcharya24&repo=Acharya-Hospital&theme=nord&title_color=7dd3fc&icon_color=7dd3fc&text_color=7dd3fc&border_color=7dd3fc" alt="Acharya-Hospital repo card" />
  </a>
</p>

| Layer | Technology |
|:--|:--|
| Backend | Flask, Flask-Mail |
| Machine Learning | scikit-learn, pandas, NumPy, joblib |
| Database | SQLite |
| Analytics & Reports | Matplotlib, ReportLab (PDF) |
| Frontend | Jinja HTML templates |
| Deployment | Gunicorn (Procfile) |

**Code →** [github.com/MeetAcharya24/Acharya-Hospital](https://github.com/MeetAcharya24/Acharya-Hospital)

<br/>

### 03 &nbsp;/&nbsp; GraphRAG — Multi-hop Question Answering

A GraphRAG app for questions that need more than one fact to answer. Upload PDF, TXT or Markdown documents, and it extracts entities into a Neo4j knowledge graph. Each answer cites its sources and shows the multi-hop graph path that links the supporting facts. Access is password-protected and rate-limited, and the whole stack runs on free tiers.

<p align="center">
  <a href="https://github.com/MeetAcharya24/graphRAG">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=MeetAcharya24&repo=graphRAG&theme=nord&title_color=7dd3fc&icon_color=7dd3fc&text_color=7dd3fc&border_color=7dd3fc" alt="graphRAG repo card" />
  </a>
</p>

| Layer | Technology |
|:--|:--|
| Backend | FastAPI, Uvicorn |
| Knowledge Graph & Vectors | Neo4j AuraDB (graph + vector index) |
| LLM | Gemini Flash (answers), Flash-Lite (entity extraction), Gemini embeddings; Anthropic optional |
| Retrieval | Multi-hop graph traversal with cited source trail |
| Testing | pytest (offline fakes + live suite) |
| Deployment | Render |

**Live →** [graphrag-bb8z.onrender.com](https://graphrag-bb8z.onrender.com/) &nbsp;·&nbsp; **Code →** [github.com/MeetAcharya24/graphRAG](https://github.com/MeetAcharya24/graphRAG)

<br/>

## Tech Stack

<p align="center"><sub><b>LANGUAGES</b></sub><br/>
  <img src="https://skillicons.dev/icons?i=python&theme=dark" alt="Python" />
</p>

<p align="center"><sub><b>FRONTEND</b></sub><br/>
  <img src="https://skillicons.dev/icons?i=react,nextjs,html&theme=dark" alt="React, Next.js, HTML" />
</p>

<p align="center"><sub><b>BACKEND</b></sub><br/>
  <img src="https://skillicons.dev/icons?i=fastapi,flask&theme=dark" alt="FastAPI, Flask" />
</p>

<p align="center"><sub><b>AI &amp; DATA</b></sub><br/>
  <img src="https://skillicons.dev/icons?i=sklearn,sqlite&theme=dark" alt="scikit-learn, SQLite" /><br/>
  <img src="https://img.shields.io/badge/Neo4j-0f172a?style=flat-square&logo=neo4j&logoColor=7dd3fc" alt="Neo4j" />
  <img src="https://img.shields.io/badge/LangChain-0f172a?style=flat-square&logo=langchain&logoColor=7dd3fc" alt="LangChain" />
  <img src="https://img.shields.io/badge/Google%20ADK-0f172a?style=flat-square&logo=google&logoColor=7dd3fc" alt="Google ADK" />
  <img src="https://img.shields.io/badge/Gemini-0f172a?style=flat-square&logo=googlegemini&logoColor=7dd3fc" alt="Gemini" />
  <img src="https://img.shields.io/badge/ElevenLabs-0f172a?style=flat-square&logo=elevenlabs&logoColor=7dd3fc" alt="ElevenLabs" />
</p>

<p align="center"><sub><b>DEV TOOLS</b></sub><br/>
  <img src="https://skillicons.dev/icons?i=git,github&theme=dark" alt="Git, GitHub" />
</p>

<br/>

## GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=MeetAcharya24&show_icons=true&include_all_commits=true&count_private=true&theme=nord&title_color=7dd3fc&icon_color=7dd3fc&text_color=7dd3fc&border_color=7dd3fc&ring_color=7dd3fc" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MeetAcharya24&layout=compact&langs_count=6&theme=nord&title_color=7dd3fc&text_color=7dd3fc&border_color=7dd3fc" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=MeetAcharya24&theme=nord&border=7dd3fc&ring=7dd3fc&fire=7dd3fc&currStreakLabel=7dd3fc&sideLabels=7dd3fc&dates=d8dee9" alt="GitHub streak" />
</p>

## Trophies

<p align="center">
  <img src="https://github-trophies.vercel.app/?username=MeetAcharya24&theme=nord&no-frame=true&no-bg=true&margin-w=6&row=1&column=7" alt="GitHub trophies" />
</p>

## Contribution Activity

<p align="center">
  <img width="100%" src="https://ghchart.rshah.org/7dd3fc/MeetAcharya24" alt="Contribution calendar" />
</p>

<br/>

## Connect

<p align="center">
  <a href="https://www.linkedin.com/in/meet-acharya/">
    <img src="https://img.shields.io/badge/LinkedIn-meet--acharya-7dd3fc?style=for-the-badge&logo=linkedin&logoColor=7dd3fc&labelColor=0f172a" alt="LinkedIn" />
  </a>
  <a href="https://www.instagram.com/_master_meet_/">
    <img src="https://img.shields.io/badge/Instagram-__master__meet__-7dd3fc?style=for-the-badge&logo=instagram&logoColor=7dd3fc&labelColor=0f172a" alt="Instagram" />
  </a>
</p>

<!-- ═══════════════════════════════  FOOTER  ═══════════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7dd3fc,45:1e3a5f,100:0f172a&height=120&section=footer&animation=twinkling" alt="" width="100%" />
</p>
