---
summary: "Workspace template for PLAYBOOK.md"
read_when:
  - Bootstrapping a workspace manually
  - Starting a new project
---

# PLAYBOOK.md — Project Name

Your project bible. The authoritative source for vision, architecture, phases, and decisions. Reference this when you need the big picture. Update it when significant decisions are made.

---

## 🎯 Vision

*What is this project? What problem does it solve? One paragraph that captures the essence.*

Example:
> A real-time analytics dashboard that transforms raw event streams into actionable insights. Not just charts — intelligent alerts, anomaly detection, and automated recommendations.

---

## 🏗️ Architecture

*How is the system structured? What are the key components and how do they interact?*

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   Frontend  │ ──▶ │     API     │ ──▶ │  Database   │
└─────────────┘     └─────────────┘     └─────────────┘
                           │
                           ▼
                    ┌─────────────┐
                    │   Workers   │
                    └─────────────┘
```

### Key Components

| Component | Purpose | Tech |
|-----------|---------|------|
| Frontend | User interface | React, Vite |
| API | Business logic | FastAPI |
| Database | Persistence | PostgreSQL |
| Workers | Background jobs | Celery |

### Principles

- *Principle 1* — Why it matters
- *Principle 2* — Why it matters
- *Principle 3* — Why it matters

---

## 📋 Phases

### ✅ Phase 1: Foundation (DONE)
- [x] Project setup and tooling
- [x] Basic data models
- [x] Core API endpoints

### 🔄 Phase 2: Core Features (IN PROGRESS)
- [x] User authentication
- [ ] Dashboard views
- [ ] Data visualization

### 📋 Phase 3: Advanced (PLANNED)
- [ ] Real-time updates
- [ ] Alert system
- [ ] Export/reporting

### 🔮 Phase 4: Scale (FUTURE)
- [ ] Multi-tenant support
- [ ] API rate limiting
- [ ] Performance optimization

---

## 📌 Decision Log

*Record significant decisions and their reasoning. Future-you will thank present-you.*

| Date | Decision | Reasoning |
|------|----------|-----------|
| YYYY-MM-DD | Chose PostgreSQL over SQLite | Need concurrent writes, JSON support |
| YYYY-MM-DD | REST API, not GraphQL | Team familiarity, simpler caching |
| YYYY-MM-DD | Monorepo structure | Shared types, atomic deploys |

---

## 📁 Key Files

*Quick reference for important files. Update as the project grows.*

| What | Where |
|------|-------|
| API routes | `backend/app/routes/` |
| Data models | `backend/app/models/` |
| Frontend pages | `frontend/src/pages/` |
| Config | `config/` |
| Docs | `docs/` |

---

## 📏 Rules

*Project-specific conventions and guardrails.*

1. **Rule name** — What to do and why
2. **Rule name** — What to do and why
3. **Rule name** — What to do and why

---

## Usage Tips

**PLAYBOOK.md vs TASK.md:**
- PLAYBOOK.md = the map (where are we going, how do we get there)
- TASK.md = the compass (where are we right now, what's the next step)

**When to update PLAYBOOK.md:**
- New phase starts or completes
- Significant architectural decision made
- New principle or rule established
- Key file locations change

**Keep phases honest.** Mark things DONE only when they're actually done. Use ✅ 🔄 📋 🔮 to show status at a glance.
