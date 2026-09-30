<p align="center">
  <img src="./assets/profile-cover.svg" alt="Mrunmayee Daware profile cover" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/Mrun25"><img src="https://img.shields.io/badge/github-Mrun25-0d1117?style=flat-square&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/mrunmayee-daware-b270362a0/"><img src="https://img.shields.io/badge/linkedin-Mrunmayee_Daware-0d1117?style=flat-square&logo=linkedin&logoColor=8B5CF6" /></a>
  <a href="mailto:mrunmayeesdaware25@gmail.com"><img src="https://img.shields.io/badge/email-mrunmayeesdaware25%40gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=22D3EE" /></a>
</p>

I like building AI systems where the model gets to reason, but the surrounding system still knows when to verify, constrain, or correct it.
Most of my work sits around fine-tuning, NLP safety, agentic workflows, retrieval, and production ML systems — the part where a model stops being an isolated experiment and becomes something that has to handle data, failure modes, APIs, deployment, and real users.
What I build
- Model adaptation & fine-tuning — LoRA/PEFT, TRL, quantization, data normalization, train/validation pipelines, and model evaluation.
- NLP safety & model supervision — crisis classification, deterministic pre-filters, critic/refine loops, and systems where an LLM is not allowed to be the only safety boundary.
- Agentic systems — retrieval, memory, self-correction, multi-provider orchestration, and tool-driven workflows.
- Production ML products — APIs, databases, Docker, AWS, schedulers, OAuth, automated tests, and CI/CD around ML systems.
Flagship work
<p align="center">
  <a href="https://github.com/Mrun25/Hearth_Emotional-Companion"><img width="48%" src="./assets/card-hearth.svg" alt="Hearth — emotionally intelligent AI companion" /></a>
  <a href="https://github.com/Mrun25/WatchTower"><img width="48%" src="./assets/card-watchtower.svg" alt="WatchTower — passive AI agent supervision" /></a>
</p>

<p align="center">
  <a href="https://github.com/Mrun25/GiSTo"><img width="48%" src="./assets/card-gisto.svg" alt="GiSTo — GST ITC risk intelligence" /></a>
  <a href="https://github.com/Mrun25/Niche-Inbox"><img width="48%" src="./assets/card-niche-inbox.svg" alt="Niche Inbox — personalized news digest automation" /></a>
</p>

The engineering behind them
- Hearth explores model behavior and safety as an engineering problem: a draft → critic → refine loop, an independent DistilBERT crisis classifier, a deterministic keyword safety layer, and a configurable fine-tuning pipeline using LoRA/PEFT, TRL, and quantization.
- WatchTower supervises AI coding agents without letting the LLM become the source of truth. The codebase relationship map is built mechanically, while Mistral is used only as an advisory reasoning layer for prompt refinement, explanation, and context-aware chat.
- GiSTo is a GST ITC risk-intelligence platform built around clean system boundaries: FastAPI + PostgreSQL/Alembic, a React CA dashboard, supplier filing-history risk scoring, a swappable GSP adapter, Telegram integration, and Docker Compose.
- Niche Inbox is an end-to-end automation pipeline: NewsAPI ingestion → Mistral summarization → per-recipient APScheduler jobs → Gmail OAuth2 delivery, deployed for continuous operation on AWS EC2.
Selected collaborative work
- MNEME — sovereign memory infrastructure for AI agents. I worked on the frontend & compliance UI, GDPR flows, Memory Market, and protocol/infrastructure pieces. The project won Monad Blitz Pune V2.
- fumii — physical AI companion with local memory and provenance intelligence. My work focused on AI/LLM integration, prompt engineering, personality/emotion behavior, and desktop/emotion logic.
- Lumi — accessibility-focused voice guidance system. I worked on the voice & inference pipeline, including ASR/TTS, language detection, and interaction flow.
- EPFO Validator — hackathon prototype developed jointly with Hassan Rehman, focused on validation workflows and product execution.
Applied ML & data work
- Fraud & Anomaly Detection — deterministic fraud rules + Isolation Forest + XGBoost + SHAP explainability, composite risk scoring, and Power BI/HTML dashboards.
- Customer Churn Analysis using R — logistic regression, churn segmentation, and business-oriented interpretation.
- Marketing Funnel & A/B Testing — funnel analysis, statistical experimentation, SQL views, and Power BI reporting.
- Agentic Study Planner — memory-driven multi-agent planning with adaptive replanning and Google Calendar synchronization.
Selected recognition
<table align="center">
  <tr>
    <td align="center" width="185">
      <sub><b>Monad Blitz Pune V2</b></sub><br>
      <sub>MNEME</sub><br>
      <sub><b>WINNER</b></sub>
    </td>
    <td align="center" width="185">
      <sub><b>iQOO Pune City Battle</b></sub><br>
      <sub>Lumi</sub><br>
      <sub><b>TOP 22 FINALIST</b></sub>
    </td>
    <td align="center" width="185">
      <sub><b>I-HACK · IIT Bombay</b></sub><br>
      <sub>2025</sub><br>
      <sub><b>SELECTED / FINALIST</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="185">
      <sub><b>IEEE Tech for Good</b></sub><br>
      <sub>2026</sub><br>
      <sub><b>HACKATHON</b></sub>
    </td>
    <td align="center" width="185">
      <sub><b>Google Solution Challenge</b></sub><br>
      <sub>2025</sub><br>
      <sub><b>PARTICIPANT</b></sub>
    </td>
    <td align="center" width="185">
      <sub><b>Bluestock Fintech</b></sub><br>
      <sub>Feb 2026 – Apr 2026</sub><br>
      <sub><b>SDE INTERN</b></sub>
    </td>
  </tr>
</table>

The stack I reach for
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,ts,react,nodejs,fastapi,flask,postgres,docker,aws,git,github&perline=12" alt="core stack" />
</p>

<p align="center">
  <code>LoRA / PEFT</code> ·
  <code>TRL</code> ·
  <code>BitsAndBytes</code> ·
  <code>DistilBERT</code> ·
  <code>Hugging Face</code> ·
  <code>RAG</code> ·
  <code>agentic self-correction</code> ·
  <code>Mistral</code> ·
  <code>scikit-learn</code> ·
  <code>SHAP</code> ·
  <code>OAuth2</code> ·
  <code>CI/CD</code>
</p>

Experience & education
<table>
  <tr>
    <td width="50%">
      <b>Bluestock Fintech</b><br>
      <sub>SDE Intern · Feb 2026 – Apr 2026 · Remote</sub><br><br>
      <sub>Worked on a production-ready corporate blog platform spanning authentication, CMS, SEO/SSG/ISR, database design, and CI/CD.</sub>
    </td>
    <td width="50%">
      <b>B.E. Artificial Intelligence</b><br>
      <sub>Zeal College of Engineering & Research · SPPU</sub><br><br>
      <sub>CGPA: <b>9.71 / 10</b></sub>
    </td>
  </tr>
</table>

<details>
<summary><b>Certifications & programs</b></summary>
<br>

- Google Responsible AI Certification
- Google Gen AI Study Jam
- Microsoft Data Analytics 101
- Deloitte Virtual Internship Program (2025)
</details>

Visitor counter
<p align="center">
  <img src="https://count.getloli.com/@Mrun25?name=Mrun25&theme=rule34&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto" alt="moe visitor counter" />
</p>
