<div align="center">

<img src="public/logo.svg?v=2" alt="web-clone" width="100" height="100" />

# web-clone

**Clone any website into a clean, modern Next.js codebase — powered by AI**

<p>
<a href="https://github.com/mocasus/web-clone/blob/master/LICENSE"><img src="https://img.shields.io/github/license/mocasus/web-clone?style=flat-square&color=blue" alt="License"/></a>
<a href="https://github.com/mocasus/web-clone/stargazers"><img src="https://img.shields.io/github/stars/mocasus/web-clone?style=flat-square&color=yellow" alt="Stars"/></a>
<a href="https://github.com/mocasus/web-clone/network/members"><img src="https://img.shields.io/github/forks/mocasus/web-clone?style=flat-square&color=orange" alt="Forks"/></a>
<a href="https://github.com/mocasus/web-clone/issues"><img src="https://img.shields.io/github/issues/mocasus/web-clone?style=flat-square&color=red" alt="Issues"/></a>
<a href="https://github.com/mocasus/web-clone/pulls"><img src="https://img.shields.io/github/issues-pr/mocasus/web-clone?style=flat-square&color=purple" alt="PRs"/></a>
<img src="https://img.shields.io/github/last-commit/mocasus/web-clone?style=flat-square&color=green" alt="Last Commit"/>
<img src="https://img.shields.io/github/repo-size/mocasus/web-clone?style=flat-square&color=teal" alt="Repo Size"/>
</p>

<p>
<img src="https://img.shields.io/github/package-json/v/mocasus/web-clone?style=flat-square&color=blueviolet&label=version" alt="Version"/>
<img src="https://img.shields.io/badge/Next.js-16-black?style=flat-square&logo=next.js" alt="Next.js"/>
<img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=white" alt="React"/>
<img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/Tailwind-4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind"/>
<img src="https://img.shields.io/badge/Node-24+-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node"/>
<img src="https://img.shields.io/badge/shadcn/ui-latest-000000?style=flat-square&logo=shadcnui&logoColor=white" alt="shadcn"/>
<img src="https://img.shields.io/badge/Docker-ready-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
</p>

[**Quick Start**](#-quick-start) · [**Supported IDEs**](#-supported-ai-agents--ides) · [**Live Demo**](#-live-demo) · [**Showcase**](#-showcase) · [**Contributing**](CONTRIBUTING.md)

</div>

---

<details open>
<summary><b>🇬🇧 English</b></summary>

<br>

Point your AI agent at any URL. It inspects the page, extracts design tokens and assets, writes component specs, then dispatches parallel builders to reconstruct every section as production-grade Next.js + TypeScript + Tailwind.

### ✨ Features

- 🎯 **One-command clone** — `/clone-website <url>` and walk away
- 🎨 **Design token extraction** — colors, spacing, typography → Tailwind config
- 🧩 **Component-first** — every section a typed, reusable React component
- ⚡ **Parallel builders** — multiple sections built concurrently
- 📸 **Visual diff** — side-by-side comparison with the original
- 🐳 **Docker-ready** — dev + prod containers included
- 🤖 **15+ AI agents supported** — see grid below

</details>

<details>
<summary><b>🇮🇩 Bahasa Indonesia</b></summary>

<br>

Arahin AI agent kamu ke URL mana aja. Dia inspeksi halaman, ekstrak design token + asset, tulis spek komponen, terus dispatch builder paralel buat ngebangun ulang tiap section jadi Next.js + TypeScript + Tailwind production-grade.

### ✨ Fitur

- 🎯 **Sekali jalan langsung kelar** — `/clone-website <url>` terus tinggal
- 🎨 **Ekstrak design token** — warna, spacing, typography → Tailwind config
- 🧩 **Komponen-first** — tiap section komponen React reusable & typed
- ⚡ **Builder paralel** — banyak section dibangun bareng
- 📸 **Visual diff** — bandingin side-by-side sama original
- 🐳 **Docker ready** — container dev + prod udah ada
- 🤖 **15+ AI agent** — lihat grid di bawah

</details>

---

## 🤖 Supported AI Agents & IDEs

This template ships with native skill/command configurations for every major AI coding agent. Just open the repo in your tool of choice — the `/clone-website` command is already wired up.

<div align="center">

| | Agent | Config | | | Agent | Config |
|---|---|---|---|---|---|---|
| <img src="https://img.shields.io/badge/-D77655?style=for-the-badge&logo=anthropic&logoColor=white" height="22"/> | **Claude Code** | `.claude/` | | <img src="https://img.shields.io/badge/-007ACC?style=for-the-badge&logo=cursor&logoColor=white" height="22"/> | **Cursor** | `.cursor/` |
| <img src="https://img.shields.io/badge/-FF9900?style=for-the-badge&logo=amazon&logoColor=white" height="22"/> | **Amazon Q** | `.amazonq/` | | <img src="https://img.shields.io/badge/-6E40C9?style=for-the-badge&logo=github&logoColor=white" height="22"/> | **Augment** | `.augment/` |
| <img src="https://img.shields.io/badge/-412991?style=for-the-badge&logo=openai&logoColor=white" height="22"/> | **OpenAI Codex** | `.codex/` | | <img src="https://img.shields.io/badge/-1A1A1A?style=for-the-badge&logo=continue&logoColor=white" height="22"/> | **Continue** | `.continue/` |
| <img src="https://img.shields.io/badge/-4285F4?style=for-the-badge&logo=google&logoColor=white" height="22"/> | **Gemini CLI** | `.gemini/` | | <img src="https://img.shields.io/badge/-FF6B35?style=for-the-badge&logo=openai&logoColor=white" height="22"/> | **OpenCode** | `.opencode/` |
| <img src="https://img.shields.io/badge/-009BFA?style=for-the-badge&logo=windsurf&logoColor=white" height="22"/> | **Windsurf** | `.windsurf/` | | <img src="https://img.shields.io/badge/-CC2244?style=for-the-badge&logo=aider&logoColor=white" height="22"/> | **Aider** | `.aider.conf.yml` |
| <img src="https://img.shields.io/badge/-0E1116?style=for-the-badge&logo=visualstudiocode&logoColor=white" height="22"/> | **Cline** | `.clinerules` | | <img src="https://img.shields.io/badge/-FFAA00?style=for-the-badge&logo=jetbrains&logoColor=white" height="22"/> | **JetBrains Junie** | `.junie/` |
| <img src="https://img.shields.io/badge/-084CCF?style=for-the-badge&logo=zedindustries&logoColor=white" height="22"/> | **Zed** | `.zed/` | | <img src="https://img.shields.io/badge/-FF5722?style=for-the-badge&logo=amazonaws&logoColor=white" height="22"/> | **Kiro** | `.kiro/` |
| <img src="https://img.shields.io/badge/-9333EA?style=for-the-badge&logo=bytedance&logoColor=white" height="22"/> | **Trae** | `.trae/` | | <img src="https://img.shields.io/badge/-EC4899?style=for-the-badge&logo=rocket&logoColor=white" height="22"/> | **Roo Code** | `.roo/` |
| <img src="https://img.shields.io/badge/-10B981?style=for-the-badge&logo=hashnode&logoColor=white" height="22"/> | **Kilo Code** | `.kilocode/` | | <img src="https://img.shields.io/badge/AGENTS-808080?style=for-the-badge" height="22"/> | **AGENTS.md** | universal |

</div>

> **Universal fallback:** `AGENTS.md`, `CLAUDE.md`, `GEMINI.md` at repo root — any agent that reads these will pick up the operating manual automatically.

---

## 🚀 Quick Start

> Click **Use this template** on GitHub instead of forking directly.

```bash
# 1. Clone your new repo
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO

# 2. Install dependencies (Node 24+ required)
npm install

# 3. Start your AI agent (Claude Code recommended)
claude --chrome

# 4. Run the clone skill
/clone-website https://stripe.com

# 5. Develop locally
npm run dev
```

Open `http://localhost:3000` — your clone will be there.

---

## 📐 How It Works

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

---

## 🎬 Live Demo

### Build Verification

Verified on a fresh clone (Debian 12, Node 24.18.0, 945MB RAM):

```bash
$ git clone https://github.com/mocasus/web-clone.git && cd web-clone

$ npm install
added 625 packages, audited 626 packages in 19s    ✓

$ npm run build
▲ Next.js 16.2.1 (Turbopack)
  Creating an optimized production build ...
✓ Compiled successfully in 6.3s
  Running TypeScript ...
  Finished TypeScript in 4.0s    ✓ no type errors
  Collecting page data ...
✓ Generating static pages (4/4) in 208ms

Route (app)
┌ ○ /
└ ○ /_not-found
○  (Static)  prerendered as static content
```

✅ **All checks pass** — `npm install` clean, `npm run build` exits 0, TypeScript happy, static generation complete in <500ms.

Full log: [`docs/build-verification.md`](docs/build-verification.md)

### Before → After

A real-world clone, side-by-side with the source. This is the actual output from running `/clone-website` on a public landing page:

<div align="center">

<img src="docs/design-references/comparison.png" alt="Before vs After comparison" width="100%"/>

<sub><i>Left: original site · Right: AI-cloned Next.js rebuild — pixel-perfect match in colors, spacing, typography</i></sub>

</div>

---

## 🎨 Showcase

Projects built with `web-clone`:

| Site | Demo | Source |
|------|------|--------|
| _Add your clone here_ | — | — |

Want yours listed? Open a PR adding your row to this table.

---

## 🛠️ Tech Stack

- **Framework:** Next.js 16 (App Router, Turbopack)
- **Language:** TypeScript 5
- **Styling:** Tailwind CSS 4
- **Components:** Base UI + shadcn/ui
- **Container:** Docker + docker-compose
- **AI Agents:** 15+ supported (see grid above)
- **Node:** 24+ required

---

## 📂 Project Structure

```
web-clone/
├── .claude/  .cursor/  .amazonq/  ...   # 15+ AI agent configs
├── docs/                                 # Design references & guides
│   ├── design-references/                # Before/after screenshots
│   └── research/                         # Per-site extraction artifacts
├── public/                               # Static assets, logo
├── scripts/                              # Build & utility scripts
├── src/                                  # Next.js source
├── AGENTS.md   CLAUDE.md   GEMINI.md     # Universal agent manuals
└── ...
```

---

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). For security issues, see [SECURITY.md](SECURITY.md).

## 📄 License

[MIT](LICENSE) © 2026 mocasus

---

<div align="center">

**Built with ⚡ by [@mocasus](https://github.com/mocasus)** · Contact: [Telegram @rubuskap](https://t.me/rubuskap)

</div>
