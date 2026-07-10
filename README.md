<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:0369a1,100:7dd3fc&height=200&section=header&text=Umer%20Malik&fontSize=56&fontColor=ffffff&animation=twinkling&desc=Machine%20Learning%20Engineer%20%E2%80%A2%20GenAI%20%E2%80%A2%20Computer%20Vision&descSize=18&descAlignY=78&fontAlignY=42" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=7DD3FC&center=true&vCenter=true&width=650&lines=Machine+Learning+Engineer;Production+AI+Agents+%7C+LangGraph+%2B+RAG;Deepfake+Detection+%7C+Computer+Vision;PyTorch+%7C+TensorFlow+%7C+FastAPI+%7C+Docker;Shipping+ML+systems%2C+not+just+notebooks" alt="Typing SVG"/>

<br/><br/>

<img src="https://img.shields.io/badge/%F0%9F%9F%A2_OPEN_TO_WORK-ML_%2F_AI_Engineer_Roles-7dd3fc?style=for-the-badge&labelColor=0f172a"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Umer553&style=for-the-badge&color=7dd3fc&label=PROFILE+VIEWS"/>
&nbsp;
<img src="https://img.shields.io/github/followers/Umer553?style=for-the-badge&logo=github&color=7dd3fc&labelColor=0f172a&label=FOLLOWERS"/>

</div>

<br/>

## 🧠 Who I Am

```typescript
const umer = {
  title: "Machine Learning Engineer @ Forrof",
  education: "BS Computer Science — University of Lahore",
  location: "Lahore, Pakistan 🇵🇰",
  stack: {
    languages: ["Python", "TypeScript", "SQL"],
    aiMl: ["PyTorch", "TensorFlow", "Transformers", "scikit-learn", "OpenCV", "YOLOv5"],
    genAi: ["LangChain", "LangGraph", "CrewAI", "RAG", "ChromaDB", "pgvector", "Mem0"],
    backend: ["FastAPI", "Flask", "PostgreSQL", "Redis", "Celery", "Docker", "Nginx"],
    observability: ["Langfuse", "Grafana"],
  },
  launchedProjects: [
    "Product_recommendation_agent — production-grade LangGraph agent with grounded recs",
    "Youtube_knowledge_assistant — multi-video RAG chatbot with timestamped answers",
    "RecruitIQ — AI resume screening with 4-layer BERT NER pipeline",
    "DeepShield — generalizable deepfake detector (in active development)",
    "AI_powered_Smart_Dustbin — CV waste classification + IoT",
  ],
  status: "Building AI agents & RAG systems in production 🚀",
  openTo: ["ML/AI Engineer roles (remote & on-site)", "AI automation collaborations"],
};
```

<br/>

<div align="center">

# 🚀 Featured Projects

</div>

### 🤖 Product Recommendation Agent

<div align="center">
<a href="https://github.com/Umer553/Product_recommendation_agent">
</a>
</div>

A production-grade AI agent that holds multi-turn conversations, retrieves products, grounds every recommendation in **live web pricing data**, and explains each decision with structured reasoning traces and 0–100 confidence scores. Authenticated, observable, async, containerized, and deployed on a self-hosted VPS.

| Layer | Technology |
|---|---|
| 🕸️ Agent Orchestration | LangGraph (with grounding-validator hallucination guard) |
| 🧠 Memory | Mem0 + pgvector (persistent cross-session) |
| 🌐 Live Grounding | Tavily web-pricing sub-agent |
| ⚡ API | FastAPI · JWT auth · SlowAPI rate limiting · SSE streaming |
| 🔄 Async Pipeline | Celery 5 + Redis Pub/Sub |
| 📈 Observability | Langfuse + Grafana |
| 🚢 Deployment | Docker + Nginx + SSL (self-hosted VPS) |

<div align="center">

[![Code](https://img.shields.io/badge/View_Code-0f172a?style=for-the-badge&logo=github&logoColor=7dd3fc)](https://github.com/Umer553/Product_recommendation_agent)

</div>

---

### 🎬 YouTube Knowledge Assistant

<div align="center">
<a href="https://github.com/Umer553/Youtube_knowledge_assistant">
</a>
</div>

A multi-video RAG chatbot that lets you **chat with YouTube videos** — timestamped answers linking to the exact moment, cross-video comparison, comment sentiment analysis, and auto-generated flashcards & quizzes, all behind smart intent-based query routing.

| Layer | Technology |
|---|---|
| 🤖 LLM | GPT-4o-mini |
| 🔗 Orchestration | LangChain (intent routing: Q&A / summarize / compare / quiz) |
| 🗄️ Vector Store | ChromaDB |
| 📝 Transcripts | YouTube captions → Whisper fallback |
| 💬 Sentiment | VADER + LLM-clustered themes |
| 🖥️ UI | Streamlit (dark glassmorphism, conversation memory) |

<div align="center">

[![Code](https://img.shields.io/badge/View_Code-0f172a?style=for-the-badge&logo=github&logoColor=7dd3fc)](https://github.com/Umer553/Youtube_knowledge_assistant)

</div>

---

### 📄 RecruitIQ — AI Resume Screening

<div align="center">
<a href="https://github.com/Umer553/AI_powered_Resume_screening-">
</a>
</div>

End-to-end resume screening that ranks candidates against a job description using semantic similarity, multi-layer skill matching, and domain-aware scoring — with a **4-layer cascading BERT NER pipeline** for candidate identity extraction.

| Layer | Technology |
|---|---|
| 📑 Parsing | pdfplumber (2-column aware) → Tesseract OCR fallback |
| 🪪 Identity (NER) | dslim/bert-base-NER + spaCy cascade |
| 🎯 Skill Matching | exact → fuzzy (rapidfuzz) → semantic (MiniLM) |
| 🏆 Scoring & Ranking | Domain-aware weighted scoring, batch pipeline, JSON/CSV export |
| 📊 Dashboard | Streamlit (radar charts, analytics, NER badges) |

<div align="center">

[![Code](https://img.shields.io/badge/View_Code-0f172a?style=for-the-badge&logo=github&logoColor=7dd3fc)](https://github.com/Umer553/AI_powered_Resume_screening-)

</div>

---

### 🛡️ DeepShield &nbsp; <img src="https://img.shields.io/badge/⚡_in_active_development-7dd3fc?style=flat-square&labelColor=0f172a"/>

<div align="center">
<a href="https://github.com/Umer553/DeepShield">
</a>
</div>

A generalizable deepfake image/video detector with an end-to-end inference service — built to hold up on *unseen* datasets, not just the training benchmark. Evolves my earlier VGG16 + BiLSTM detector (94% frame-level accuracy) into a production-grade system.

| Layer | Technology |
|---|---|
| 🧬 Models | EfficientNet / ViT backbones |
| 🧪 Evaluation | Cross-dataset generalization benchmarks |
| 🔍 Explainability | Grad-CAM heatmaps |
| ⚡ Serving | ONNX Runtime + FastAPI inference service |
| 📦 Packaging | Docker |

<div align="center">

[![Code](https://img.shields.io/badge/View_Code-0f172a?style=for-the-badge&logo=github&logoColor=7dd3fc)](https://github.com/Umer553/DeepShield)

</div>

<br/>

## 📦 More Projects

| Project | What it does | Tech |
|---|---|---|
| 🗑️ [AI_powered_Smart_Dustbin](https://github.com/Umer553/AI_powered_Smart_Dustbin) | CV-based waste detection & classification (recyclable / organic / plastic / metal) with automatic compartment routing — AI + IoT for smart waste management | TensorFlow/Keras CNN · Computer Vision · IoT · Flutter |
| 🔁 [Loop_IQ_backend](https://github.com/Umer553/Loop_IQ_backend) | Backend API service | Python |

<br/>

<div align="center">

# 🛠️ Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=py,ts,js&theme=dark"/>

**AI / ML**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,sklearn&theme=dark"/>

<img src="https://img.shields.io/badge/LangChain-7dd3fc?style=for-the-badge&logo=langchain&logoColor=0f172a"/> <img src="https://img.shields.io/badge/LangGraph-7dd3fc?style=for-the-badge&logoColor=0f172a"/> <img src="https://img.shields.io/badge/CrewAI-7dd3fc?style=for-the-badge&logoColor=0f172a"/> <img src="https://img.shields.io/badge/ChromaDB-7dd3fc?style=for-the-badge&logoColor=0f172a"/> <img src="https://img.shields.io/badge/Hugging_Face-7dd3fc?style=for-the-badge&logo=huggingface&logoColor=0f172a"/> <img src="https://img.shields.io/badge/Streamlit-7dd3fc?style=for-the-badge&logo=streamlit&logoColor=0f172a"/>

**Backend & Infra**

<img src="https://skillicons.dev/icons?i=fastapi,flask,postgres,redis,docker,nginx&theme=dark"/>

**Frontend**

<img src="https://skillicons.dev/icons?i=react,html,css,vite&theme=dark"/>

**Dev & Observability Tools**

<img src="https://skillicons.dev/icons?i=grafana,git,github,vscode,anaconda,linux&theme=dark"/>

</div>

<br/>

<div align="center">

# 📊 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=Umer553&show_icons=true&theme=nord&title_color=7dd3fc&icon_color=7dd3fc&border_color=7dd3fc&rank_icon=github" height="170"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Umer553&layout=compact&theme=nord&title_color=7dd3fc&border_color=7dd3fc" height="170"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Umer553&background=2E3440&border=7DD3FC&stroke=7DD3FC&ring=7DD3FC&fire=7DD3FC&currStreakNum=ECEFF4&sideNums=ECEFF4&currStreakLabel=7DD3FC&sideLabels=7DD3FC&dates=88C0D0"/>

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=Umer553&theme=onedark&no-frame=true&no-bg=true&row=1&column=7&margin-w=8"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Umer553&bg_color=2e3440&color=7dd3fc&line=7dd3fc&point=eceff4&area=true&hide_border=false&border_color=7dd3fc" width="95%"/>

</div>

<br/>

<div align="center">

# 🤝 Connect With Me

<a href="mailto:umeraftab.mk@gmail.com"><img src="https://img.shields.io/badge/Email-umeraftab.mk%40gmail.com-7dd3fc?style=for-the-badge&logo=gmail&logoColor=0f172a"/></a>
&nbsp;
<a href="https://github.com/Umer553"><img src="https://img.shields.io/badge/GitHub-Umer553-7dd3fc?style=for-the-badge&logo=github&logoColor=0f172a"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:0369a1,100:7dd3fc&height=140&section=footer" width="100%"/>

</div>

