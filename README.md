<div align="center">

<img src="public/logo.svg" alt="web-clone" width="100" height="100" />

# web-clone

**Clone any website into a clean, modern Next.js codebase — powered by AI**

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mocasus/web-clone?style=flat-square&color=yellow)](https://github.com/mocasus/web-clone/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/mocasus/web-clone?style=flat-square&color=green)](https://github.com/mocasus/web-clone/commits)
[![Issues](https://img.shields.io/github/issues/mocasus/web-clone?style=flat-square&color=red)](https://github.com/mocasus/web-clone/issues)
[![Version](https://img.shields.io/badge/version-1.0.0-blueviolet?style=flat-square)](CHANGELOG.md)
[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js)](https://nextjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)

[**Quick Start**](#-quick-start) · [**How It Works**](#-how-it-works) · [**Showcase**](#-showcase) · [**Contributing**](CONTRIBUTING.md)

</div>

---

<details open>
<summary><b>🇬🇧 English</b></summary>

<br>

Point your AI agent at any URL. It inspects the page, extracts design tokens and assets, writes component specs, then dispatches parallel builders to reconstruct every section as production-grade Next.js + TypeScript + Tailwind.

> **Recommended:** [Claude Code](https://docs.anthropic.com/en/docs/claude-code) with Opus 4.7 — but works with any modern AI coding agent.

### ✨ Features

- 🎯 **One-command clone** — `/clone-website <url>` and walk away
- 🎨 **Design token extraction** — colors, spacing, typography → Tailwind config
- 🧩 **Component-first architecture** — every section is a typed, reusable React component
- ⚡ **Parallel builders** — multiple sections built concurrently
- 📸 **Visual diff** — side-by-side comparison with the original
- 🐳 **Docker-ready** — dev + prod containers included
- 🤖 **Multi-agent compatible** — Claude Code, Cursor, GitHub Copilot

### 🚀 Quick Start

> Click **Use this template** on GitHub instead of forking directly.

```bash
# 1. Clone your new repo
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO

# 2. Install dependencies
npm install

# 3. Start your AI agent (Claude Code recommended)
claude --chrome

# 4. Run the clone skill
/clone-website https://stripe.com

# 5. Develop locally
npm run dev
```

Open `http://localhost:3000` — your clone will be there.

### 📐 How It Works

```
┌─────────────────┐    ┌──────────────────┐    ┌──────────────────┐
│  Target URL     │───▶│  AI Inspector    │───▶│ Design Tokens    │
│                 │    │  (DOM + Visual)  │    │ Component Specs  │
└─────────────────┘    └──────────────────┘    └────────┬─────────┘
                                                        │
                                                        ▼
┌─────────────────┐    ┌──────────────────┐    ┌──────────────────┐
│  Next.js App    │◀───│  Parallel        │◀───│  Builder         │
│  (Production)   │    │  Section Builds  │    │  Orchestrator    │
└─────────────────┘    └──────────────────┘    └──────────────────┘
```

</details>

<details>
<summary><b>🇮🇩 Bahasa Indonesia</b></summary>

<br>

Arahin AI agent kamu ke URL mana aja. Dia inspeksi halamannya, ekstrak design token + asset, tulis spek komponen, terus dispatch builder paralel buat ngebangun ulang tiap section jadi Next.js + TypeScript + Tailwind production-grade.

> **Rekomendasi:** [Claude Code](https://docs.anthropic.com/en/docs/claude-code) dengan Opus 4.7 — tapi bisa pake AI coding agent apapun.

### ✨ Fitur

- 🎯 **Sekali jalan langsung kelar** — `/clone-website <url>` terus tinggal
- 🎨 **Ekstrak design token** — warna, spacing, typography → langsung jadi Tailwind config
- 🧩 **Arsitektur komponen** — tiap section komponen React yang reusable & typed
- ⚡ **Builder paralel** — banyak section dibangun bareng
- 📸 **Visual diff** — bandingin side-by-side sama original
- 🐳 **Docker siap pakai** — container dev + prod udah ada
- 🤖 **Multi-agent** — Claude Code, Cursor, GitHub Copilot

### 🚀 Quick Start

> Klik **Use this template** di GitHub, jangan fork langsung.

```bash
# 1. Clone repo baru kamu
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO

# 2. Install dependencies
npm install

# 3. Start AI agent (Claude Code direkomendasi)
claude --chrome

# 4. Jalankan skill clone
/clone-website https://stripe.com

# 5. Develop lokal
npm run dev
```

Buka `http://localhost:3000` — clone-nya udah jadi.

</details>

---

## 🎨 Showcase

Projects built with `web-clone`:

| Site | Demo | Source |
|------|------|--------|
| _Add your clone here_ | — | — |

Want yours listed? Open a PR adding your row to this table.

---

## 🛠️ Tech Stack

- **Framework:** Next.js 15 (App Router)
- **Language:** TypeScript 5
- **Styling:** Tailwind CSS 4
- **Components:** Radix UI + shadcn/ui
- **Container:** Docker + docker-compose
- **AI Agents:** Claude Code, Cursor, Copilot

---

## 📂 Project Structure

```
web-clone/
├── .claude/         # Claude Code skills & commands
├── .cursor/         # Cursor IDE rules
├── docs/            # Design references & guides
├── public/          # Static assets, logo
├── scripts/         # Build & utility scripts
├── src/             # Next.js source
└── AGENTS.md        # AI agent operating manual
```

---

## 🤝 Contributing

Contributions welcome! See [CONTRIBUTING.md](CONTRIBUTING.md). For security issues, see [SECURITY.md](SECURITY.md).

## 📄 License

[MIT](LICENSE) © 2026 Andika

---

<div align="center">

**Built with ⚡ by [@mocasus](https://github.com/mocasus)**

Contact: [Telegram @rubuskap](https://t.me/rubuskap)

[![Version](https://img.shields.io/badge/version-1.0.0-blueviolet?style=flat-square)](CHANGELOG.md)

</div>
