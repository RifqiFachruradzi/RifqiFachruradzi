<h1 align="center">Hi, I'm Rifqi Fachruradzi 👋</h1>
<p align="center">
  <b>Full-Stack Developer · Next.js · React · TypeScript · AI Agents</b><br/>
  I build business systems that companies actually run on (POS, inventory, procurement, accounting, logistics)<br/>
  and plug AI into them: OCR invoice reading, AI assistants, and multi-agent workflows.
</p>

<p align="center">
  <a href="https://portoleaf.vercel.app"><img src="https://img.shields.io/badge/Portfolio-2E7D32?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  <a href="https://visual-office.vercel.app"><img src="https://img.shields.io/badge/Featured_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
</p>

---

### 🚀 What I do

- Build **end-to-end web apps**: UI, APIs, auth, databases, deployment, all live on Vercel.
- Model **real business processes**: PR → PO → Goods Receipt → Invoice → Payment, double-entry journals, stock cards, approvals, audit logs.
- Integrate **LLMs (Gemini, Claude)** as assistants, report generators, and hierarchical multi-agent systems.
- Connect systems together: apps that read each other's data (read-only, safely) to produce insights.

---

### ⭐ Featured — [Visual Office](https://github.com/RifqiFachruradzi/visual-office) · [Live](https://visual-office.vercel.app)

> A 2.5D / 3D virtual office where every employee is an **AI agent**. You're the Boss: create divisions, hire agents, give orders, and watch them brief, work, and report back.

<a href="https://visual-office.vercel.app"><img src="https://raw.githubusercontent.com/RifqiFachruradzi/visual-office/main/demo.gif" alt="Visual Office demo: the Boss gives an order and AI agents start working" width="100%"/></a>

- **Hierarchical multi-agent system**: Boss → Director → Lead → Staff, with summaries rolling up the chain, rate-limited queues and auto-retry.
- **3D rendering** with three.js from GLB assets, 2D fallback, and 6 visual themes.
- **Live business data**: agents read my MiniMarket and Warehouse apps to write stock and sales reports.
- **Telegram bot** to command the office remotely.
- **Programmatic video pipeline**: AI storyboard → Remotion worker on a VPS → MP4 with TTS narration and subtitles. AI-generated animation code is validated and auto-repaired before rendering.

---

### 🏢 Business Systems

| Project | What it does | Stack |
|---|---|---|
| [MiniMarket ERP](https://github.com/RifqiFachruradzi/MIniMarket-APP) · [Live](https://mini-market-app-wheat.vercel.app) | POS, inventory, cash & bank, AR/AP, with automatic **double-entry journals** feeding the Balance Sheet, P&L and Cash Flow | Next.js 15 · Turso · Drizzle · Zod |
| [AP Hub](https://github.com/RifqiFachruradzi/account-payable-app) · [Live](https://account-payable-app.vercel.app) | Accounts payable with **OCR invoice scanning**, auto document matching and **3-way matching**, tiered payment approval | React 19 · TypeScript · Tesseract.js · Zustand |
| [Procura](https://github.com/RifqiFachruradzi/procurement-management-system) · [Live](https://procurement-management-system-three.vercel.app) | Procurement from PR to payment: 2-level approvals, vendor portal, goods receipt, journal vouchers | Next.js 16 · Zustand · Immer |
| [Gudang-Document](https://github.com/RifqiFachruradzi/Gudang-Document) · [Live](https://gudang-document.vercel.app) | Paperless warehouse receiving: PO matching, photo inspection, digital signatures, real-time stock, AI assistant | Next.js 16 · Upstash Redis · Gemini |
| [Accounting System](https://github.com/RifqiFachruradzi/laporan-keuangan-app) · [Live](https://laporan-keuangan-app-delta.vercel.app) | Journals, general ledger, trial balance, AR/AP aging, financial statements | Next.js · Supabase (RLS) |
| [Ekspedisi App](https://github.com/RifqiFachruradzi/ekspedisi-app) · [Live](https://ekspedisi-app.vercel.app) | Trucking operations: orders, drivers, fleet, work orders, trip cost & revenue, settlement | Next.js · TypeScript |

### 🧩 More Projects

| Project | What it does |
|---|---|
| [SimpananMu](https://github.com/RifqiFachruradzi/SimpananMu) · [Live](https://simpanan-mu.vercel.app) | Personal finance tracker with budgets, savings goals, PDF reports and an **AI finance buddy** (Gemini) |
| [STRIDE+](https://github.com/RifqiFachruradzi/stride-running-dashboard) · [Live](https://coros-running-dashboard.vercel.app) | Running dashboard synced from COROS via OAuth 2.0 and Vercel Cron |
| [SinergiPro](https://github.com/RifqiFachruradzi/SinergiPro) · [Live](https://sinergi-pro.vercel.app) | Landing page and workforce booking / partner signup with camera selfie and WhatsApp handoff |
| [agent-skills](https://github.com/RifqiFachruradzi/agent-skills) | Agent Skills for AI coding agents: root-cause debugging, verification, Git hygiene |

---

### 🛠️ Tech Stack

**Languages:** TypeScript, JavaScript, Python<br/>
**Frontend:** Next.js (App Router), React 19, Tailwind CSS v4, Zustand, Redux Toolkit, Recharts, three.js<br/>
**Backend:** Next.js Route Handlers & Server Actions, Node.js, FastAPI, Vercel Functions<br/>
**Data:** Turso/libSQL + Drizzle, Supabase (Postgres + RLS), Upstash Redis, Vercel Blob<br/>
**AI:** Gemini API, Claude API, Tesseract.js OCR, Remotion<br/>
**DevOps:** Vercel, Linux VPS, Podman, OAuth 2.0, Vercel Cron

<p align="center"><i>Open to full-stack / AI engineering roles and freelance projects.</i></p>
