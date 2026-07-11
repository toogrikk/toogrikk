<!-- toogrikk — GitHub Profile README -->
<p align="center">
  <img src="https://raw.githubusercontent.com/toogrikk/toogrikk/main/assets/github_purple_banner.png" alt="toogrikk's banner" width="100%" />
</p>

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+toogrikk+%F0%9F%91%8B;Python+%2F+Fullstack+Developer;AI+%2F+RAG+Solutions+Architect" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="http://t.me/Toogrikk"><img src="https://img.shields.io/badge/Telegram-black?style=for-the-badge&logo=telegram&logoColor=white&color=6D28D9" alt="Telegram" /></a>
  <a href="https://www.instagram.com/toogrikk/"><img src="https://img.shields.io/badge/Instagram-black?style=for-the-badge&logo=instagram&logoColor=white&color=A855F7" alt="Instagram" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=toogrikk&style=for-the-badge&color=8A2BE2&label=PROFILE+VIEWS" alt="Profile views" />
</p>

<img src="https://raw.githubusercontent.com/toogrikk/toogrikk/main/assets/divider.svg" width="100%" />

## 🧠 About Me

I build **AI-powered backend systems** that solve real operational problems — not demos. My core focus is combining local LLMs, vector search (RAG), and computer vision with production-grade architecture (async Python, PostgreSQL, containerized deployments).

```yaml
role: Python / Fullstack Developer & AI-RAG Solutions Architect
focus: [Local LLM pipelines, RAG systems, FastAPI backends, Telegram automation]
currently_building: AI ServiceDesk — an enterprise support-automation ecosystem
philosophy: "Zero hallucinations. The AI only knows what the knowledge base tells it."
```

- 🔭 **Currently building:** an AI ServiceDesk ecosystem — a Telegram bot that resolves employee IT tickets automatically using local vision + RAG.
- ⚙️ **Comfortable in:** Python, C++, C#, JavaScript.
- 🗄️ **Designing data layers with:** PostgreSQL, SQLite, ChromaDB (vector search).
- 💬 **Ask me about:** RAG pipelines, FastAPI dashboards, OCR + vision integration, Telegram bot architecture.

<img src="https://raw.githubusercontent.com/toogrikk/toogrikk/main/assets/divider.svg" width="100%" />

## 💻 Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <br/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <br/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/ChromaDB-8A2BE2?style=for-the-badge&logoColor=white" alt="ChromaDB" />
  <br/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Aiogram_3-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Aiogram" />
</p>

<img src="https://raw.githubusercontent.com/toogrikk/toogrikk/main/assets/divider.svg" width="100%" />

## 🛠️ Featured Projects

### ⚡ [AI ServiceDesk Ecosystem](https://github.com/toogrikk/AI-Assistant)
**Production-tested enterprise support automation** — a Telegram bot that acts as first-line IT support, using local AI + computer vision instead of button menus.

<table>
<tr>
<td width="60%">

**How it works:**
- 🗣️ Understands free-form messages (typos, slang, no scripted menus)
- 👁️ Reads employee screenshots with a local **EasyOCR** pipeline and cross-references them against the reported issue to catch mismatches automatically
- 🧠 Answers strictly from a **RAG knowledge base** (ChromaDB + `nomic-embed-text`) — zero hallucinated advice
- 📋 Walks users step-by-step through approved procedures, remembering session state
- 🎫 Auto-escalates unresolved issues to a **React + FastAPI admin dashboard**, where the ticket is instantly queued to a free operator
- ✍️ Admins edit the knowledge base through a live split-screen Markdown editor — changes re-embed into the vector store **without restarting the bot**

</td>
<td width="40%">

**Stack**
```
Backend:   Python · FastAPI · asyncio
ORM:       SQLAlchemy + PostgreSQL
Bot:       aiogram 3
AI:        Ollama (Llama 3.2 Vision)
Search:    ChromaDB · nomic-embed-text
Vision:    EasyOCR (RU/UA/EN)
Frontend:  React admin dashboard
```

**Status:** ✅ Fully deployed & production-tested

</td>
</tr>
</table>

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Llama_3.2_Vision-orange?style=flat-square&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-8A2BE2?style=flat-square" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
</p>

---

### 🍽️ [Coffee Shop Web](https://github.com/toogrikk/-offee-shop-web) `Work in Progress ⏳`
A full-stack ordering platform for a coffee shop — menu browsing, product details, and online checkout, built on a clean backend architecture.

**Stack:** C# (ASP.NET Core) · SQL Server · (planned) React frontend

**Planned:**
- 🛒 Menu, product pages, and cart-to-checkout flow
- 🔐 User authentication + order history
- 🧑‍💼 Admin panel for menu & order management

**Status:** 🟡 Backend architecture defined — frontend & ordering flow in active development

<p align="left">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white" />
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" />
</p>

<img src="https://raw.githubusercontent.com/toogrikk/toogrikk/main/assets/divider.svg" width="100%" />

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=toogrikk&show_icons=true&theme=tokyonight&bg_color=0D1117&title_color=A855F7&icon_color=A855F7&text_color=C9D1D9&border_color=8A2BE2&border_radius=10" alt="toogrikk's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=toogrikk&layout=compact&theme=tokyonight&bg_color=0D1117&title_color=A855F7&text_color=C9D1D9&border_color=8A2BE2&border_radius=10" alt="toogrikk's Top Languages" width="42%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=toogrikk&theme=tokyonight&background=0D1117&ring=A855F7&fire=A855F7&currStreakLabel=A855F7&currStreakNum=C9D1D9&sideNums=C9D1D9&sideLabels=C9D1D9&border=8A2BE2&border_radius=10" alt="toogrikk's GitHub Streak" width="98%" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=toogrikk&theme=tokyo-night&bg_color=0D1117&color=A855F7&line=8A2BE2&point=C9D1D9&border=8A2BE2" alt="toogrikk's activity graph" width="98%" />
</p>

<img src="https://raw.githubusercontent.com/toogrikk/toogrikk/main/assets/divider.svg" width="100%" />

<p align="center">
  <i>💜 Building systems that actually solve problems, one commit at a time.</i>
</p>
