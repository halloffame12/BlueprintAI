
# 🚀 BlueprintAI

### *From idea → architecture → code → live preview*

BlueprintAI is an **AI-powered system architect** that converts a simple project idea into a **complete, production-ready software system** — including **architecture, tech stack decisions, real code, diagrams, and live previews**.

It works for **everyone**:

* 🧑‍💻 Developers → via a powerful CLI
* 🧑‍🎨 Non-developers → via a visual Web UI

---

## ✨ What Problem Does It Solve?

Building a real application requires:

* Choosing the right tech stack
* Designing architecture
* Writing backend & frontend code
* Setting up authentication & database
* Creating diagrams & documentation

This takes **days or weeks**.

👉 **BlueprintAI does it in minutes.**

---

## 🧠 What BlueprintAI Does

From a single idea like:

> *“Online exam system for colleges with login and results”*

BlueprintAI automatically:

✅ Analyzes the idea
✅ Chooses the **latest optimal tech stack**
✅ Explains **why each technology was chosen**
✅ Generates **real, runnable code**
✅ Creates an **architecture diagram**
✅ Provides **live frontend preview**
✅ Allows updates using plain English

---

## 🧩 Core Features

### 🏗️ AI System Architecture

* Intelligent tech stack selection
* Transparent reasoning for every decision
* Multiple stack suggestions (optional)

---

### 🧑‍💻 Full Code Generation (REAL CODE)

Generates:

* Frontend (Next.js + Tailwind)
* Backend (NestJS / Fastify / Elysia / Bun)
* Database schema & migrations
* Authentication (Clerk / Supabase / Firebase)
* API routes (REST / GraphQL / gRPC)
* README & environment templates

❌ No boilerplate
❌ No pseudo-code

---

### 📊 Architecture Diagrams

* Auto-generated Mermaid diagrams
* Always synced with the blueprint
* Export as PNG / PDF

---

### 🌐 Web UI (For Everyone)

* Describe your idea in plain English
* See AI reasoning & tech stack
* Explore generated code
* Live frontend preview
* Update app using natural language
* Download full project

---

### ⚙️ CLI (For Developers)

A powerful CLI for local development:

```bash
npx blueprintai init
npx blueprintai update
npx blueprintai preview
npx blueprintai explain
npx blueprintai export
```

* Generates full projects locally
* Safe updates using diffs
* Git repo auto-initialized
* Works on macOS, Linux, Windows

---

## 🧠 How It Works (High Level)

```
Idea → AI Reasoning → Architecture Blueprint
     → Code Generator → Diagram Generator
     → Web UI / CLI Output
```

The **backend AI engine** is the single source of truth for both Web and CLI.

---

## 🏗️ Tech Stack (Latest Only)

### Frontend

* Next.js 14+
* React 19
* TailwindCSS v4
* Framer Motion
* Three.js (3D UI)
* Mermaid.js
* Monaco Editor

### Backend

* Node.js 20+ / Bun
* NestJS / Fastify / Elysia (AI-chosen)
* TypeScript (strict)
* Gemini API (reasoning)

### Databases

* PostgreSQL 16
* MongoDB 7
* SQLite
* Supabase / Firebase

### Auth (Only if Full-Stack App)

* Clerk
* Supabase Auth
* Firebase Auth

---

## 📁 Project Outputs

Each generation produces:

```
generated-project/
├── frontend/
├── backend/
├── database/
├── blueprint.json
├── architecture.mmd
├── README.md
└── .env.example
```

---

## 📦 Blueprint Format (Example)

```json
{
  "frontend": "Next.js",
  "backend": "NestJS",
  "database": "PostgreSQL",
  "authentication": "Clerk",
  "api_style": "REST",
  "deployment": ["Vercel", "Render"],
  "reasoning": {
    "frontend": "SSR and performance",
    "backend": "Scalable architecture",
    "database": "Relational consistency"
  }
}
```

---

## 🔁 Updating a Project

You can update your app using plain English:

> “Add real-time notifications”
> “Switch database to MongoDB”
> “Add admin dashboard”

BlueprintAI:

* Updates the blueprint
* Regenerates only affected code
* Preserves your changes

---

## 🧪 Hackathon Ready

* ⏱️ End-to-end demo in under **2 minutes**
* 🎯 Clear AI reasoning
* 🧠 Architecture visibility
* 💻 Real code output
* 🔥 Strong wow-factor

---

## 🛡️ Reliability & Safety

* Non-destructive code updates
* Versioned blueprints
* Graceful AI failure handling
* Modular, extensible design

---

## 📜 License

**MIT License**
Free & open-source.
Contributions welcome ❤️

---

## 👥 Team

* **Sumit** — Backend, AI logic, code generation, CLI
* **Aditi** — Frontend, Web UI, diagrams, UX
* **Divya** — Documentation, templates, demos
* **Anmol** — CLI testing, QA, validation

---
