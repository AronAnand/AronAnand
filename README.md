<div align="center">

# Aron C Anand

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3200&pause=900&color=00D9FF&center=true&vCenter=true&width=760&lines=AI%2FML+Platform+Engineer;LLMs+%C2%B7+RAG+%C2%B7+Agentic+AI+Systems;I+ship+production+pipelines%2C+not+demos" alt="AI/ML Platform Engineer — LLMs, RAG, Agentic AI Systems" />

<br>

[![Open to work](https://img.shields.io/badge/Open_to_work-Available_immediately-00D9FF?style=flat-square&labelColor=0D1117)](mailto:aronc.anand3@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-aroncanand-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0D1117)](https://www.linkedin.com/in/aroncanand/)
[![Email](https://img.shields.io/badge/Email-aronc.anand3-EA4335?style=flat-square&logo=gmail&logoColor=white&labelColor=0D1117)](mailto:aronc.anand3@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-Aron--droid-FFA116?style=flat-square&logo=leetcode&logoColor=white&labelColor=0D1117)](https://leetcode.com/u/Aron-droid/)
[![Profile Views](https://komarev.com/ghpvc/?username=AronAnand&color=00D9FF&style=flat-square&label=visitors&labelColor=0D1117)](https://github.com/AronAnand)

</div>

---

```
$ aron --status

⟨ agent ⟩ loading profile ...

  ├─ role ........... Software Engineer II  ·  AI/ML Platform
  ├─ experience ..... ~3 yrs shipping production LLM systems
  ├─ domain ......... RAG · multi-agent orchestration · AI microservices
  ├─ base ........... Kochi, Kerala, India
  ├─ education ...... B.Tech CSE, CUSAT  ·  8.3/10
  └─ status ......... AVAILABLE IMMEDIATELY → no notice period
                      open to LLM research · AI products · collaborations

⟨ agent ⟩ ready. 
```

---

## ▸ The system I keep building

Most of my work collapses into one shape: **retrieve the truth, orchestrate the reasoning, validate the output.** Here's that shape, drawn with the tools I actually use in production.

```
                       user query
                            │
                            ▼
                   ┌────────────────┐
                   │    FastAPI     │   async · Pydantic-typed contracts
                   └───────┬────────┘
                           ▼
                ┌──────────────────────┐
                │  Agent Orchestration │   CrewAI · LangChain
                └──────────┬───────────┘
            ┌──────────────┼──────────────┐
            ▼              ▼              ▼
      ┌──────────┐   ┌──────────┐   ┌──────────┐
      │ RESEARCH │   │  EXTRACT │   │ VALIDATE │
      │  Serper  │──▶│Firecrawl │──▶│ Pydantic │
      │  Tavily  │   │ scraping │   │  cross-  │
      │          │   │          │   │  check   │
      └──────────┘   └──────────┘   └────┬─────┘
                                         │  clean, reconciled facts
                                         ▼
                     ┌───────────────────────────────┐
                     │       Retrieval Layer         │
                     │  semantic + hybrid search      │
                     │  Qdrant · Pinecone             │
                     │  Neo4j · PostgreSQL · MongoDB  │
                     └───────────────┬───────────────┘
                                     ▼
                       ┌──────────────────────────┐
                       │      LLM Synthesis       │   OpenAI · Azure OpenAI · Gemini
                       │   grounded · cited · typed│
                       └──────────────┬───────────┘
                                      ▼
                              Docker  ·  Azure  ·  CI/CD
```

> The interesting part is never the model call. It's the schema design, the service boundaries, and the validation layer that stops a confident hallucination from reaching a user.

---

## ▸ Production scorecard

Numbers from systems live in front of real users at **PriceSenz** *(Sep 2023 → Jul 2026 · promoted to Software Engineer II, May 2026)*.

| What I changed | Approach | Result |
|:---|:---|:---|
| Customer-facing conversational AI | Multi-agent workflows over OpenAI + Gemini for document intelligence | **93%** satisfaction rate |
| Infrastructure spend | FastAPI + Docker microservices, redesigned schema & API architecture | **−27%** cost |
| Response quality | Advanced prompt engineering across OpenAI & Meta AI | **+41%** accuracy |
| Model efficiency | Knowledge-distillation pipeline in Python | **+35%** performance |
| Assessment delivery | Adaptive engine generating questions from live user responses | real-time evaluation |

I own end-to-end design decisions on these: table structure, service boundaries, API contracts.

---

## ▸ Selected systems

<table>
<tr><td width="50%" valign="top">

### Multi-Agent School Data Aggregation
`CrewAI` `Serper` `Tavily` `Firecrawl` `Python`

Three specialized agents that compile verified school profiles from the open web.

- **Research agent** discovers sources per target school
- **Scraping agent** extracts contacts, admissions, facilities, reviews
- **Validation agent** reconciles across sources and flags contradictions

*Built for SchoolPath.*

</td><td width="50%" valign="top">

### RFP Analysis & Automation
`Python` `NLP` `Embeddings` `Semantic Retrieval`

An end-to-end pipeline that turns public procurement noise into ranked opportunities.

- Scrapes **170+ government portals**
- Embeds and ranks RFPs by company fit
- Auto-generates pre-filled submission PDFs via markdown extraction + LLM drafting

*Built for PriceSenz.*

</td></tr>
<tr><td width="50%" valign="top">

### Job ↔ Recruiter Matchmaking Platform
`FastAPI` `Neo4j` `Vector DBs` `SQLAlchemy` `Pydantic`

**Sole AI/ML engineer.** Resume and JD extraction with typed validation, feeding a hybrid graph + vector store for semantic matching.

- Modular services: parsing → matching → assessment → ranking
- Automated assessment generation for shortlisted candidates via Gemini

*Built for Talentz AI.*

</td><td width="50%" valign="top">

### RAG Chatbots — Schools & Civic Services
`FastAPI` `Azure OpenAI` `RAG` `Google Maps API`

Two grounded assistants in production:

- **School bot** — admissions, policy, curriculum queries answered from source documents, cutting hallucinated answers
- **Civic bot** — verified citizens report issues (potholes) and track resolution; natural-language lookup of nearby services

*Built for PriceSenz.*

</td></tr>
</table>

---

## ▸ Finalist — Gen AI Exchange Hackathon

<div align="center">

**World's Largest Agentic AI Hackathon · Bengaluru**

<img src="https://github.com/AronAnand/AronAnand/blob/main/Hack2skill-Certificate.png" alt="Gen AI Exchange Hackathon Finalist Certificate" width="520"/>

</div>

Automated **multigrade classroom scheduling** for rural schools — one teacher, several grades, one timetable that has to work.

`Gemini API` for constraint reasoning · `FastAPI` backend · live web-search retrieval for dynamic data · conflict-free generation over a REST architecture.

---

## ▸ Stack

Everything here is something I've shipped with — not something I've read about.

<div align="center">

**Language & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=0D1117)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white&labelColor=0D1117)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white&labelColor=0D1117)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white&labelColor=0D1117)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white&labelColor=0D1117)

**LLM & Agentic**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white&labelColor=0D1117)
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0D1117)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white&labelColor=0D1117)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white&labelColor=0D1117)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A5F?style=flat-square&logoColor=white&labelColor=0D1117)

**Retrieval & Data**

![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white&labelColor=0D1117)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white&labelColor=0D1117)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white&labelColor=0D1117)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white&labelColor=0D1117)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white&labelColor=0D1117)

**Agent Tooling & Web Data**

![Serper](https://img.shields.io/badge/Serper-1A73E8?style=flat-square&logoColor=white&labelColor=0D1117)
![Tavily](https://img.shields.io/badge/Tavily-6D28D9?style=flat-square&logoColor=white&labelColor=0D1117)
![Firecrawl](https://img.shields.io/badge/Firecrawl-FF6A00?style=flat-square&logoColor=white&labelColor=0D1117)

**Cloud & DevOps**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0D1117)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white&labelColor=0D1117)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black&labelColor=0D1117)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white&labelColor=0D1117)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white&labelColor=0D1117)

</div>

---

## ▸ Activity

<div align="center">

<a href="https://github.com/AronAnand">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=AronAnand&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=C9D1D9&count_private=true&include_all_commits=true" alt="GitHub stats" />
</a>
<a href="https://git.io/streak-stats">
<img height="165" src="https://streak-stats.demolab.com?user=AronAnand&theme=tokyonight&hide_border=true&background=0D1117&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF" alt="GitHub streak" />
</a>

</div>

---

<div align="center">

### Let's build something that survives contact with real users.

**Open to:** LLM research · AI product engineering · agentic system design · hackathon teams

[![LinkedIn](https://img.shields.io/badge/Say_hello_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117)](https://www.linkedin.com/in/aroncanand/)
[![Email](https://img.shields.io/badge/aronc.anand3@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117)](mailto:aronc.anand3@gmail.com)

<sub><i>"The question of whether a computer can think is no more interesting than the question of whether a submarine can swim." — E. W. Dijkstra</i></sub>

</div>
