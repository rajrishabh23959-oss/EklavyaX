<div align="center">

  <img src="frontend/assets/img/logo.png" alt="EklavyaX Logo" width="120" height="120" style="border-radius: 50%; filter: drop-shadow(0 6px 16px rgba(238, 180, 62, 0.45));" />

  # 🏹 EklavyaX

  ### Next-Gen Gamified STEM & AI Tutoring Platform Bridging Classrooms, Labs, and Curiosity

  <p align="center">
    <strong>Inspired by Eklavya's timeless devotion to self-mastery — empowered by multi-provider AI, interactive physics simulations, and verifiable gamification mechanics.</strong>
  </p>

  <p align="center">
    <a href="https://github.com/fastapi/fastapi"><img src="https://img.shields.io/badge/FastAPI-0.115-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/></a>
    <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.10+"/></a>
    <a href="https://groq.com/"><img src="https://img.shields.io/badge/AI%20Engine-Groq%20%7C%20Gemini%20%7C%20OpenRouter-f55036?style=for-the-badge&logo=openai&logoColor=white" alt="Multi-LLM"/></a>
    <a href="https://www.postgresql.org/"><img src="https://img.shields.io/badge/PostgreSQL%20%7C%20SQLite-Ready-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="Database"/></a>
    <a href="https://katex.org/"><img src="https://img.shields.io/badge/KaTeX-LaTeX%20Math-3298dc?style=for-the-badge&logo=latex&logoColor=white" alt="KaTeX"/></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge" alt="License MIT"/></a>
  </p>

  <p align="center">
    <a href="https://eklavya-x.vercel.app/"><img src="https://img.shields.io/badge/Live%20Demo-eklavya--x.vercel.app-00C7B7?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo"/></a>
    <a href="https://github.com/rajrishabh23959-oss/EKLAVYAX"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repository"/></a>
  </p>

  <p align="center">
    <a href="#-quick-start">🚀 <strong>Get Started</strong></a> •
    <a href="#-screenshot-gallery">📸 <strong>Screenshots</strong></a> •
    <a href="#-core-features">✨ <strong>Features</strong></a> •
    <a href="#-system-architecture">🏗️ <strong>Architecture</strong></a> •
    <a href="#-tech-stack">🛠️ <strong>Tech Stack</strong></a> •
    <a href="#-roadmap">🗺️ <strong>Roadmap</strong></a> •
    <a href="#-team--credits">👥 <strong>Team</strong></a>
  </p>

  <br />

  <img src="frontend/assets/screenshots/banner-min.png" alt="EklavyaX Platform Banner" width="100%" style="border-radius: 14px; box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);" />

</div>

<br />

---

## 🧭 Table of Contents

- [💡 Why EklavyaX?](#-why-eklavyax)
- [✨ Core Features](#-core-features)
  - [🎓 Student Portal](#-student-portal)
  - [👨‍🏫 Teacher & Faculty Hub](#-teacher--faculty-hub)
  - [🏫 Principal Institutional Oversight](#-principal-institutional-oversight)
  - [🛡️ Anti-Gaming Safeguards](#️-anti-gaming-safeguards)
- [📸 Screenshot Gallery](#-screenshot-gallery)
- [🏗️ System Architecture](#️-system-architecture)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Quick Start](#-quick-start)
  - [Prerequisites](#prerequisites)
  - [Installation & Local Run](#installation--local-run)
  - [Demo Accounts](#-demo-accounts)
  - [Environment Configuration (`.env`)](#-environment-configuration-backendenv)
  - [Automated Testing](#-automated-testing)
- [📁 Project Structure](#-project-structure)
- [🗺️ Roadmap](#️-roadmap)
- [👥 Team & Credits](#-team--credits)
- [📄 License](#-license)

---

## 💡 Why EklavyaX?

In the ancient epic Mahabharata, **Eklavya** mastered archery through unyielding dedication before a clay statue of Dronacharya when traditional instruction was denied to him. Today, millions of ambitious students in tier-2, tier-3, and rural schools face analogous barriers: limited laboratory equipment, understaffed faculties, and inaccessible 1-on-1 tutoring.

**EklavyaX** bridges this educational divide by transforming any low-spec web browser into an interactive, gamified STEM sanctuary:

1. **Socratic AI Tutoring, Not Cheat Prompts**: Powered by **Gravity AI**, our multi-model microservice (Groq LLaMA 3.3, Google Gemini, OpenRouter, and OpenAI) teaches first principles, parses mathematical notation into clean LaTeX formulas via KaTeX, and rewards correct post-explanation problem solving.
2. **Virtual Lab Simulations**: Students explore physical kinematics, buoyancy, Faraday's laws, chemical balancing, and mathematical proportions through PhET-powered simulations without needing expensive lab physical apparatus.
3. **High-Stakes Gamification with Real Integrity**: Learning progress is anchored by an in-platform virtual economy—**EduCoins**, XP tiers, **Faction Wars** between four ancient Houses, and daily streaks protected by streak freezes.
4. **Resilient Safeguards Engine**: A server-side anti-gaming validation pipeline ensures that rewards cannot be farmed through bot scripts, inspected browser clients, or instant automated clicks.

---

## ✨ Core Features

### 🎓 Student Portal

Designed to make independent daily STEM learning addictive, visual, and rigorous.

| Module | Features & Capabilities | Route / Page |
| :--- | :--- | :--- |
| **🤖 Gravity AI Tutor** | Conversational AI tutor delivering direct answers, intuitive step-by-step breakdowns, real-world analogies, and rendered KaTeX LaTeX equations. Supports English, Hindi, and regional explanation modes. | [`frontend/student/eklavya_ai.html`](frontend/student/eklavya_ai.html) |
| **🔬 Virtual STEM Labs** | Interactive simulations for **Physics** (forces, buoyancy, optics, electrostatics), **Chemistry** (atomic models, reaction balancing), and **Mathematics** (proportions, balancing). | [`frontend/student/lab_simulation.html`](frontend/student/lab_simulation.html) |
| **⚔️ Faction Wars** | Clan competitions where students belong to one of 4 Houses: *House Vidyut* ⚡, *House Agni* 🔥, *House Vayu* 🍃, or *House Prithvi* 🌍. Battle scores aggregate XP to determine weekly champions. | [`frontend/student/faction_wars.html`](frontend/student/faction_wars.html) |
| **🥊 Live Quiz & Battles** | Synchronous real-time quiz duels with wagered EduCoins, instant countdown timers, and accuracy bonuses. | [`frontend/student/live_battle.html`](frontend/student/live_battle.html) |
| **🪙 Virtual Economy** | Real-time **EduCoin** wallet, XP progression, daily check-in streaks, streak freezes, transaction logs, and reward incentives. | [`frontend/student/student_dashboard.html`](frontend/student/student_dashboard.html) |
| **🗂️ Spaced Repetition Flashcards** | SuperMemo-inspired SM-2 spaced repetition algorithm with dynamic ease factors, repetition counts, and due-date tracking. | [`frontend/student/flashcards.html`](frontend/student/flashcards.html) |
| **🎯 Revision Radar** | Cognitive retention tracker scheduling reviews at optimal spaced intervals (**Day 1**, **Day 7**, and **Day 30**) to counteract memory decay. | [`backend/app/api/routes/pedagogy.py`](backend/app/api/routes/pedagogy.py) |
| **📜 PYQ Arena** | Timed, chapter-wise Previous Year Question banks for competitive exams (**JEE Main**, **JEE Advanced**, **NEET**, and **CBSE Class 12 Boards**). | [`frontend/student/pyq_arena.html`](frontend/student/pyq_arena.html) |
| **🗺️ Concept Maps & EklavyaLens** | Visual conceptual mind-mapping (`mindmaps.html`) and geospatial interactive map layers (`eklavyalens.html`). | [`frontend/student/mindmaps.html`](frontend/student/mindmaps.html) |
| **🎓 Verified Certificates** | Cryptographically verified course completion credentials equipped with unique identification codes and shareable QR verification links. | [`frontend/student/certificates.html`](frontend/student/certificates.html) |

---

### 👨‍🏫 Teacher & Faculty Hub

Empowering educators to automate grading, monitor conceptual gaps, and run engaging classrooms.

| Module | Features & Capabilities | Route / Page |
| :--- | :--- | :--- |
| **📊 Pedagogical Analytics** | Real-time mastery analytics, accuracy heatmaps, time-on-task metrics, and flagged student weak areas. | [`frontend/teacher/analytics.html`](frontend/teacher/analytics.html) |
| **🎯 Teacher Bounty Board** | Educators post custom topical problem challenges with coin bounties. Students submit answers for review and coin rewards. | [`backend/app/api/routes/bounties.py`](backend/app/api/routes/bounties.py) |
| **📝 Interactive Quiz Builder** | Visual creation interface for custom quizzes with custom time limits, coin rewards, and detailed answer explanations. | [`frontend/teacher/quiz_builder.html`](frontend/teacher/quiz_builder.html) |
| **📋 Assignment Management** | Create, distribute, and grade student homework with deadline trackers and individual feedback loops. | [`frontend/teacher/assignments.html`](frontend/teacher/assignments.html) |
| **💬 Doubt Resolution Desk** | 1-on-1 teacher-student question thread management with attachment support (PDF/Images) and resolution statuses. | [`frontend/teacher/doubts.html`](frontend/teacher/doubts.html) |
| **👥 Class & Roster Manager** | Section-wise student management (`10-A`, `10-B`), roll numbers, parent contact links, and student attendance logging. | [`frontend/teacher/myclass.html`](frontend/teacher/myclass.html) |

---

### 🏫 Principal Institutional Oversight

Institutional command center providing school-wide intelligence across classrooms, exams, and attendance.

| Module | Features & Capabilities | Route / Page |
| :--- | :--- | :--- |
| **🏛️ Campus-Wide KPIs** | High-level metrics tracking total enrollment, faculty headcount, student attendance rates, and average GPA/exam marks. | [`frontend/teacher/principal_dashboard.html`](frontend/teacher/principal_dashboard.html) |
| **📅 Timetable & Exams** | Class-wise period scheduling, exam scheduling, maximum/passing mark configuration, and grade distribution analysis. | [`backend/app/api/routes/principal.py`](backend/app/api/routes/principal.py) |
| **📢 Broadcast Announcements** | Campus-wide broadcast notices directed to entire schools, teachers, students, parents, or specific grades. | [`frontend/teacher/announcements.html`](frontend/teacher/announcements.html) |
| **👨‍👩‍👧 Parent Access Portal** | Guardian login portal linked via secure parent keys (`parent_access_keys`) to observe child attendance and marks. | [`frontend/student/parent_dashboard.html`](frontend/student/parent_dashboard.html) |

---

### 🛡️ Anti-Gaming Safeguards

All reward-bearing endpoints run through a fail-safe server-side validation pipeline in [`backend/app/services/safeguards.py`](backend/app/services/safeguards.py). If any validation encounters an error, rewards are **rejected**, not granted.

```
Incoming Quiz Submission
          │
          ▼
┌─────────────────────────────────┐
│ 1. validate_server_answer()     │ ──> Rejects wrong answers against server answer key
└─────────────────────────────────┘
          │
          ▼
┌─────────────────────────────────┐
│ 2. check_question_cooldown()    │ ──> Rejects answers submitted faster than 2.0s
└─────────────────────────────────┘
          │
          ▼
┌─────────────────────────────────┐
│ 3. check_and_apply_daily_cap()  │ ──> Enforces 500 EduCoins / 1000 XP daily earnings limit
└─────────────────────────────────┘
          │
          ▼
┌─────────────────────────────────┐
│ 4. grant_reward() + Audit Log   │ ──> Writes immutable event to reward_audit_logs
└─────────────────────────────────┘
          │
          ▼
┌─────────────────────────────────┐
│ 5. evaluate_suspicious_pattern()│ ──> Rolling z-score response analysis (flag-only, non-blocking)
└─────────────────────────────────┘
```

- **Server-Side Answer Validation**: The browser client never receives the correct answer index.
- **Option Order Randomization**: Multiple-choice options are shuffled per user session to defeat static scrape bots.
- **Z-Score Anomaly Flagging**: Fast response outliers with 100% accuracy are flagged for administrative review without interrupting normal gameplay.

> [!NOTE]
> Read the complete specification in [SAFEGUARDS.md](SAFEGUARDS.md).

---

## 📸 Screenshot Gallery

<div align="center">

| 🌐 Landing Page & Multi-Role Gateway | 🎓 Student Command Center & Streaks |
| :---: | :---: |
| <img src="frontend/assets/screenshots/home_page.png" alt="EklavyaX Landing Portal" width="100%" style="border-radius: 8px;"/> | <img src="frontend/assets/screenshots/student_dashboard.png" alt="Student Dashboard" width="100%" style="border-radius: 8px;"/> |
| *Chalkboard portal offering role-specific entry points* | *Gamified quest hub, streak counter, EduCoins & course progression* |

| 👨‍🏫 Teacher Analytics & Classroom Hub | 🔬 Interactive Virtual Physics & STEM Lab |
| :---: | :---: |
| <img src="frontend/assets/screenshots/teacher_dashboard.png" alt="Teacher Dashboard" width="100%" style="border-radius: 8px;"/> | <img src="frontend/assets/screenshots/lab_simulation.png" alt="Lab Simulation" width="100%" style="border-radius: 8px;"/> |
| *Teacher metrics, assignment tracker, and class analytics* | *Interactive STEM experiments: forces, buoyancy, optics & circuits* |

</div>

---

## 🏗️ System Architecture

```mermaid
flowchart TB
    subgraph Clients["🖥️ Client Tier (PWA & Responsive Web)"]
        SP["🎓 Student Portal\n(Dashboard, AI Tutor, Labs, Quizzes)"]
        TP["👨‍🏫 Teacher Hub\n(Analytics, Assignments, Doubts)"]
        PP["🏫 Principal Command\n(Institutional KPIs & Schedule)"]
        GP["👨‍👩‍👦 Parent Portal\n(Progress & Attendance)"]
    end

    subgraph Gateway["⚡ API & Gateway Layer"]
        FA["FastAPI Application (app.main:app)"]
        CORS["CORS & Request Middleware"]
        JWT["JWT Security & Bcrypt Auth (HS256)"]
        STATIC["StaticFiles Mount (Frontend Pages & PWA)"]
    end

    subgraph Services["⚙️ Backend Core Services"]
        AI["🤖 Gravity AI Microservice\n(System Prompts, LaTeX Formatter)"]
        GAME["🎮 Game Engine\n(Factions, Streaks, Wallets, Battles)"]
        SAFE["🛡️ Safeguards Pipeline\n(Cooldowns, Daily Caps, Z-Scores)"]
        PED["📈 Pedagogy Engine\n(Revision Radar, PYQ, Mastery)"]
    end

    subgraph AIProviders["🧠 Multi-LLM Provider Engine"]
        GROQ["⚡ Groq Cloud\n(LLaMA 3.3 70B - Default)"]
        GEMINI["✨ Google Gemini\n(Gemini 1.5 Flash)"]
        OR["🌐 OpenRouter\n(Unified AI Gateway)"]
        OAI["🧠 OpenAI\n(GPT-4o-mini)"]
    end

    subgraph Data["💾 Persistence & Cache Layer"]
        DB[("🗄️ Relational Database\nPostgreSQL / SQLite via SQLAlchemy 2.0")]
        REDIS[("⚡ Redis (Optional)\nLeaderboard & Battle Cache")]
        AUDIT[("📋 Reward Audit Logs\nFail-Safe Security Ledger")]
    end

    Clients -->|HTTPS / REST API| Gateway
    Gateway --> JWT
    Gateway --> STATIC
    Gateway --> Services

    AI --> AIProviders
    GAME --> DB
    GAME --> REDIS
    SAFE --> AUDIT
    PED --> DB
```

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technologies | Description |
| :--- | :--- | :--- |
| **Frontend Core** | <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript%20ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> | Semantic HTML5, Vanilla CSS design tokens, and modular modern JavaScript |
| **Mathematics & UI** | <img src="https://img.shields.io/badge/KaTeX-LaTeX-3298DC?style=flat-square&logo=latex&logoColor=white"/> <img src="https://img.shields.io/badge/FontAwesome-5.15-528DD7?style=flat-square&logo=fontawesome&logoColor=white"/> <img src="https://img.shields.io/badge/PhET-Simulations-2B579A?style=flat-square"/> | Fast LaTeX formula parsing, responsive vector iconography, interactive simulations |
| **Backend Framework** | <img src="https://img.shields.io/badge/FastAPI-0.115-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Uvicorn-ASGI-499848?style=flat-square"/> | High-performance asynchronous Python API server with OpenAPI docs |
| **ORM & Data** | <img src="https://img.shields.io/badge/SQLAlchemy-2.0-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/> | Typed 2.0 ORM mappings, zero-config local SQLite, and robust PostgreSQL migrations |
| **AI Orchestration** | <img src="https://img.shields.io/badge/Groq-LLaMA%203.3%2070B-F55036?style=flat-square"/> <img src="https://img.shields.io/badge/Google%20Gemini-1.5%20Flash-8E75C2?style=flat-square&logo=google&logoColor=white"/> <img src="https://img.shields.io/badge/OpenRouter-API-6366F1?style=flat-square"/> | Dynamic multi-model failover with Socratic prompts and token-efficient streaming |
| **Security & Auth** | <img src="https://img.shields.io/badge/PyJWT-HS256-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/> <img src="https://img.shields.io/badge/Passlib-Bcrypt-4B5563?style=flat-square"/> <img src="https://img.shields.io/badge/Pydantic-v2.9-E92063?style=flat-square&logo=pydantic&logoColor=white"/> | Secure salted password hashing, stateless Bearer tokens, strict request validation |
| **Caching & Testing** | <img src="https://img.shields.io/badge/Redis-5.2-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/pytest-8.x-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/> <img src="https://img.shields.io/badge/HTTPX-Async-1E3A8A?style=flat-square"/> | Sub-millisecond leaderboards, comprehensive async unit & safeguard test suites |
| **Deployment** | <img src="https://img.shields.io/badge/Vercel-Serverless-000000?style=flat-square&logo=vercel&logoColor=white"/> <img src="https://img.shields.io/badge/Render-Web%20Service-46E3B7?style=flat-square&logo=render&logoColor=black"/> | Pre-configured `render.yaml` and `vercel.json` deployment blueprints |

</div>

---

## 🚀 Quick Start

Get EklavyaX running on your local machine in under 5 minutes.

### Prerequisites

- **Python 3.10+** installed
- **Git** installed
- An API key for your preferred AI provider (Free Groq Cloud, Google Gemini, OpenRouter, or OpenAI)

---

### Installation & Local Run

#### 1. Clone the repository

```bash
git clone https://github.com/rajrishabh23959-oss/EKLAVYAX.git
cd EKLAVYAX
```

#### 2. Set up virtual environment

```bash
# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate

# On macOS / Linux:
source venv/bin/activate
```

#### 3. Install Python dependencies

```bash
pip install -r requirements.txt
```

#### 4. Configure environment variables

```bash
# Copy template file
cp .env.example .env
```

Open `.env` in your editor and configure your AI key. Groq provides free API keys at [console.groq.com/keys](https://console.groq.com/keys):

```ini
AI_PROVIDER=groq
GROQ_API_KEY=gsk_your_groq_api_key_here
```

#### 5. Launch the application

```bash
uvicorn app.main:app --reload --port 8000
```

The FastAPI server will automatically:
- Create and ensure all SQLite database tables (`EklavyaX.db`)
- Seed the 4 Factions (*House Vidyut, House Agni, House Vayu, House Prithvi*)
- Seed default quiz questions, active battles, and demo user accounts
- Mount and serve all frontend static files at root `http://localhost:8000/`

---

### 🔑 Demo Accounts

The database comes pre-seeded with ready-to-test role accounts:

| Portal | Role | Username / Email | Password | Direct Portal URL |
| :--- | :--- | :--- | :--- | :--- |
| 🎓 **Student** | Student (Class 10) | `student@eklavya.edu` | `Student@123` | [http://localhost:8000/student/student_login.html](http://localhost:8000/student/student_login.html) |
| 👨‍🏫 **Teacher** | Faculty (Physics) | `teacher@eklavya.edu` | `Teacher@123` | [http://localhost:8000/teacher/login.html](http://localhost:8000/teacher/login.html) |
| 👑 **Principal** | School Administrator | `principal@eklavya.edu` | `Admin@123` | [http://localhost:8000/teacher/principal_login.html](http://localhost:8000/teacher/principal_login.html) |
| 👨‍👩‍👦 **Parent** | Guardian | `parent@eklavya.edu` | `Parent@123` | [http://localhost:8000/student/parent_login.html](http://localhost:8000/student/parent_login.html) |
| 📖 **API Docs** | Swagger Interactive | — | — | [http://localhost:8000/docs](http://localhost:8000/docs) |
| 📑 **ReDoc** | API Reference | — | — | [http://localhost:8000/redoc](http://localhost:8000/redoc) |

---

### 🔑 Environment Configuration (`backend/.env`)

Below is a complete reference of configurable options with **placeholders only**:

```ini
# ─── Database ────────────────────────────────────────────────────────────────
# Use SQLite for quick local development or PostgreSQL for production
DATABASE_URL=sqlite:///./EklavyaX.db
# DATABASE_URL=postgresql://postgres:your_password@localhost:5432/eklavyax

# ─── Security & JWT ──────────────────────────────────────────────────────────
SECRET_KEY=your-super-secret-key-change-this-in-production-min-32-chars
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=60

# ─── AI Provider ─────────────────────────────────────────────────────────────
# Options: "groq" (default - ultra fast & free tier), "gemini", "openrouter", "openai"
AI_PROVIDER=groq

# Groq Cloud (https://console.groq.com/keys)
GROQ_API_KEY=your-groq-api-key-here
GROQ_MODEL=llama-3.3-70b-versatile

# Google Gemini (https://aistudio.google.com/app/apikey)
GEMINI_API_KEY=your-gemini-api-key-here
GEMINI_MODEL=gemini-1.5-flash

# OpenRouter (https://openrouter.ai/keys)
OPENROUTER_API_KEY=your-openrouter-api-key-here
OPENROUTER_MODEL=google/gemini-2.5-flash

# OpenAI (https://platform.openai.com/api-keys)
OPENAI_API_KEY=your-openai-api-key-here
OPENAI_MODEL=gpt-4o-mini

# ─── Economy & Gamification Tuning ───────────────────────────────────────────
AI_EXPLAIN_COST=10             # EduCoins charged per AI explanation
AI_REFUND_COINS=5              # Coins refunded if student subsequently answers correctly
STREAK_BONUS_COINS=5           # Daily streak check-in reward
STREAK_BONUS_XP=10             # Daily streak XP reward
BOUNTY_COMPLETION_XP=50        # XP awarded upon teacher bounty completion
NEW_USER_COINS=100             # Initial wallet balance for new students

# ─── Safeguard Thresholds ────────────────────────────────────────────────────
QUESTION_MIN_COOLDOWN_SECONDS=2.0   # Minimum delay before accepting answer submission
DAILY_MAX_COINS=500                 # Maximum coins earnable per calendar day
DAILY_MAX_XP=1000                   # Maximum XP earnable per calendar day
CAP_EXCEEDED_POLICY=reduced         # Policy when cap reached: "reject" | "zero" | "reduced"
CAP_REDUCTION_FACTOR=0.25           # Multiplier when policy is set to "reduced"

# ─── CORS & Networking ───────────────────────────────────────────────────────
CORS_ORIGINS=http://localhost:8000,http://localhost:3000,http://localhost:5173
# REDIS_URL=redis://localhost:6379/0
APP_ENV=development
```

---

### 🧪 Automated Testing

EklavyaX includes test suites covering security, game logic, safeguards, and router handlers using an isolated in-memory SQLite database:

```bash
# Navigate to backend directory
cd backend

# Run all test suites with verbose output
python -m pytest tests/ -v
```

To run individual test modules:
```bash
# Test Core Auth, Economy & AI Prompts
python -m pytest tests/test_core.py -v

# Test Faction Battles & Quiz Sessions
python -m pytest tests/test_quiz_faction.py -v

# Test Anti-Gaming Safeguards (Cooldowns, Caps, Z-Scores)
python -m pytest tests/test_safeguards.py -v
```

---

## 📁 Project Structure

```
EklavyaX/
├── api/
│   └── index.py                     # Vercel serverless ASGI gateway
├── backend/
│   ├── app/
│   │   ├── api/
│   │   │   └── routes/              # 22+ Modular API routers
│   │   │       ├── achievements.py  # Badges & milestone achievements
│   │   │       ├── analytics.py     # Student performance metrics
│   │   │       ├── auth.py          # JWT authentication & profile registration
│   │   │       ├── bounties.py      # Teacher bounty board
│   │   │       ├── certificates.py  # Verified certificate generation & QR codes
│   │   │       ├── doubts.py        # 1-on-1 student-teacher doubt desk
│   │   │       ├── economy.py       # EduCoins, streak engine & wallet transactions
│   │   │       ├── faction_wars.py  # Clan battles, house scoring & contributions
│   │   │       ├── flashcards.py    # Spaced repetition flashcards (SM-2)
│   │   │       ├── leaderboard.py   # Global & sectional leaderboards
│   │   │       ├── live_quiz.py     # Real-time quiz battle rooms
│   │   │       ├── pedagogy.py      # Revision Radar, topic mastery & weak area flags
│   │   │       ├── principal.py     # Institutional KPIs, timetable & exam results
│   │   │       ├── quiz.py          # Question sessions with anti-gaming checks
│   │   │       ├── tutor.py         # Gravity AI explanation endpoints
│   │   │       └── ...
│   │   ├── core/                    # Security, password hashing, and config models
│   │   ├── db/                      # SQLAlchemy database engine and 30+ ORM models
│   │   ├── schemas/                 # Pydantic request/response validation schemas
│   │   ├── services/
│   │   │   ├── ai_service.py        # Multi-provider LLM prompt builder & client
│   │   │   ├── game_logic.py        # Streak, faction, wallet, and battle algorithms
│   │   │   └── safeguards.py        # Fail-safe anti-cheat & audit pipeline
│   │   └── main.py                  # FastAPI application entrypoint & static mount
│   ├── tests/                       # Unit & integration pytest suites
│   ├── .env.example                 # Environment variable template
│   ├── migrate_db.py                # Database migration helper
│   └── requirements.txt             # Backend dependencies
├── frontend/
│   ├── assets/
│   │   ├── fonts/                   # Typography assets
│   │   ├── img/                     # Logos, avatars, badges, and icons
│   │   └── screenshots/             # Interface screenshots & hero graphics
│   ├── css/                         # Chalkboard design system & stylesheets
│   ├── js/                          # Client API bindings, chatbot, and UI scripts
│   ├── student/                     # 25 Student pages (Dashboard, AI, Labs, PYQ, etc.)
│   ├── teacher/                     # 13 Faculty & Principal pages (Analytics, Quizzes)
│   ├── index.html                   # Multi-role landing page & portal selector
│   ├── manifest.json                # PWA web manifest
│   └── service_worker.js            # Progressive Web App offline worker
├── render.yaml                      # Render cloud deployment blueprint
├── vercel.json                      # Vercel static & serverless routing config
├── requirements.txt                 # Root dependency reference
├── SAFEGUARDS.md                    # In-depth anti-gaming security documentation
└── README.md                        # Documentation
```

---

## 🗺️ Roadmap

- [x] **Multi-Role Authentication**: JWT-based access for Students, Teachers, Principals, and Parents.
- [x] **Gravity AI Microservice**: Socratic STEM explanations with Groq, Gemini, OpenRouter, and OpenAI.
- [x] **KaTeX Math Rendering**: Clean LaTeX equation formatting for math, physics, and chemical reactions.
- [x] **Virtual STEM Simulation Labs**: Embedded PhET simulations across Physics, Chemistry, and Math.
- [x] **Gamification Engine**: 4 ancient Houses, EduCoin wallets, daily streaks, and streak freezes.
- [x] **7-Layer Anti-Cheat Safeguards**: Cooldown timers, option shuffling, daily caps, and rolling z-scores.
- [x] **Competitive PYQ Arena**: Timed practice for JEE Main, JEE Advanced, NEET, and CBSE Class 12.
- [x] **Spaced Retrieval Engine**: Revision Radar (Day 1, 7, 30) and SM-2 flashcard intervals.
- [x] **Institutional Intelligence**: Principal dashboard with campus KPIs, faculty timetables, and exam records.
- [x] **Verified QR Certificates**: Tamper-proof certificate generation with verifiable QR endpoints.
- [ ] **Offline SQLite Sync**: Lightweight local sync for rural schools with intermittent internet connectivity.
- [ ] **Automated IP Rate-Limiting**: Token-bucket middleware protection for public API endpoints.
- [ ] **Speech-to-Speech Voice Tutor**: Multimodal conversational audio mode in regional Indian languages.

---

## 👥 Team & Credits

<div align="center">

| Contributor | Role & Contributions |
| :--- | :--- |
| [**Rishabh Raj**](https://github.com/rajrishabh23959-oss) | Project Architecture, Full-Stack Development, Gamification & AI Engine |
| **Sayan Mondal** | Core Contributor, Feature Implementation & Quality Assurance |

</div>

EklavyaX stands on the shoulders of incredible open-source projects:
- [FastAPI](https://fastapi.tiangolo.com/) by Sebastián Ramírez
- [PhET Interactive Simulations](https://phet.colorado.edu/) by University of Colorado Boulder
- [KaTeX](https://katex.org/) by Khan Academy
- [Groq Cloud](https://groq.com/) & [Google Gemini](https://ai.google.dev/)

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file or details below:

```text
MIT License

Copyright (c) 2026 EklavyaX Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

<br />

<div align="center">
  <sub>Built with ❤️ for curious students, passionate teachers, and accessible STEM education.</sub>
</div>
