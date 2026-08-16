<!-- Profile Banner -->
<p align="center">
  <a href="https://github.com/ecano08">
    <img src="./assets/banner.png" alt="Elia Cano — Software Engineer · Applied AI · Full-Stack" width="100%" />
  </a>
</p>

<p align="center">
  <strong>Software Engineer · Applied AI · Full-Stack Development</strong>
</p>

<p align="center">
  I build operational software and AI-powered systems that connect
  business logic, APIs, data, LLMs, and real-world workflows.
</p>

<p align="center">
  <a href="https://github.com/ecano08">
    <img src="https://img.shields.io/badge/GitHub-ecano08-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://github.com/ecano08/ai-logistics-copilot">
    <img src="https://img.shields.io/badge/Featured_Project-AI_Logistics_Copilot-412991?style=for-the-badge&logo=openai&logoColor=white" alt="AI Logistics Copilot" />
  </a>
</p>

---

## 👋 About Me

I'm a Software Engineer with a background in full-stack and backend development, focused on building practical systems that solve real operational problems.

My work combines traditional software engineering with Applied AI, especially systems where LLMs need to interact safely with APIs, databases, business rules, external services, and human decision-making.

I enjoy working at the intersection of:

- 🧠 Applied AI and LLM-powered systems
- ⚙️ Backend architecture and business logic
- 🌐 Full-stack applications
- 🔌 APIs and third-party integrations
- 🗄️ Relational data and PostgreSQL
- 🐳 Dockerized environments
- 🔁 CI/CD and automated testing
- 🛡️ AI safety, evaluations, and human-in-the-loop workflows

My current focus is building **production-oriented AI systems — not just chatbots**.

---

# 🚀 Featured Project

## [AI Logistics Copilot](https://github.com/ecano08/ai-logistics-copilot)

> AI-powered logistics operations copilot built around safe LLM integration, deterministic business logic, controlled tools, and human approval.

### Architecture

```text
                ┌─────────────────────────┐
                │   React + TypeScript    │
                │     Operations UI       │
                └────────────┬────────────┘
                             │
                             ▼
                ┌─────────────────────────┐
                │ Node.js + TypeScript API│
                │    Logistics Domain     │
                └───────┬─────────┬───────┘
                        │         │
                        │         └──────────► Open-Meteo
                        │
                        ▼
                ┌─────────────────────────┐
                │       PostgreSQL        │
                │    Operational Data     │
                └─────────────────────────┘

                             │
                             ▼
                ┌─────────────────────────┐
                │   Python + FastAPI      │
                │       AI Service        │
                ├─────────────────────────┤
                │ LLM Tool Calling        │
                │ Risk Engine             │
                │ Human Approval          │
                │ Evals & Safety          │
                │ Observability           │
                └────────────┬────────────┘
                             │
                             ▼
                       OpenAI API
```

### What it demonstrates

- LLM Tool Calling
- Multi-step AI workflows
- Shipment and customer lookup
- External weather API integration
- Deterministic delay-risk scoring
- Shipment risk prioritization
- Structured operational recommendations
- Human-in-the-loop escalation proposals
- AI safety evaluations
- Controlled agent behavior
- Structured observability
- PostgreSQL-backed operational data
- Docker Compose environment
- Automated testing
- GitHub Actions CI

### Example AI workflow

```text
Operator asks about SHP-1010
        ↓
LLM resolves the shipment
        ↓
Operational data is retrieved
        ↓
Deterministic risk engine evaluates:
status + ETA + events + weather
        ↓
HIGH risk / Score 90
        ↓
LLM explains the result
        ↓
Escalation is proposed
        ↓
Human approval is required
```

### Core design principle

> **AI can investigate, reason, recommend, and prepare actions — but business-critical decisions remain controlled by deterministic software and humans.**

<p align="center">
  <a href="https://github.com/ecano08/ai-logistics-copilot">
    <img src="https://img.shields.io/badge/View_Project-AI_Logistics_Copilot-181717?style=for-the-badge&logo=github&logoColor=white" alt="View AI Logistics Copilot" />
  </a>
</p>

---

# 🧠 Applied AI Engineering

I'm working with patterns used to move LLM applications beyond basic prompt/response interfaces:

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

```text
LLM Integration
Tool / Function Calling
Structured Outputs
Multi-step Workflows
Deterministic Guardrails
Human-in-the-Loop
AI Evaluations
Safety Checks
Observability
External API Integration
```

---

# 🛠️ Tech Stack

## Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)

## Data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

## Infrastructure & Tooling

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

# 🏗️ How I Approach Engineering

I like building systems from the business problem outward:

```text
Business Problem
      ↓
Discovery & Requirements
      ↓
Software Architecture
      ↓
APIs + Data
      ↓
Business Rules
      ↓
AI Where It Adds Value
      ↓
Testing + Safety
      ↓
Observability
      ↓
Real Operational Workflow
```

I'm particularly interested in systems where AI needs to work with **existing software, APIs, databases, users, and real business constraints**.

---

# 🔭 Current Focus

I'm currently deepening my experience in:

- Applied AI Engineering
- LLM-powered operational systems
- Python + FastAPI
- Node.js + TypeScript
- React + TypeScript
- Tool Calling
- Agentic workflows
- AI evaluations
- AI safety
- Observability
- Docker
- Cloud architecture
- Forward Deployed Engineering

---

# 💡 Engineering Philosophy

For business-critical AI systems, I prefer:

```text
           LLM Reasoning
                +
          Controlled Tools
                +
     Deterministic Business Logic
                +
           External APIs
                +
               Data
                +
              Tests
                +
        Human Approval
                +
         Observability
```

rather than giving an LLM unrestricted control over operational systems.

---

# 🤝 Let's Connect

I'm interested in engineering opportunities involving:

- **Applied AI**
- **AI Engineering**
- **Forward Deployed Engineering**
- **Backend Engineering**
- **Full-Stack Engineering**
- **AI-enabled operational systems**

<p align="center">
  <a href="https://github.com/ecano08">
    <img src="https://img.shields.io/badge/Explore_My_Work-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile" />
  </a>
</p>

---

<p align="center">
  <strong>Building software that connects business logic, real-world operations, and AI.</strong>
</p>
