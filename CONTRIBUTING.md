# Contributing to web-clone

Thanks for your interest in contributing! This document explains how to get involved.

## 🤝 Ways to Contribute

- **Bug reports** — found something broken? [Open an issue](https://github.com/mocasus/web-clone/issues/new)
- **Feature requests** — have an idea? Open a discussion first
- **Pull requests** — see workflow below
- **Showcase** — built something cool? Add your project to the showcase table in README
- **Documentation** — typos, clarifications, translations always welcome

## 🔧 Development Setup

```bash
git clone https://github.com/mocasus/web-clone.git
cd web-clone
npm install
npm run dev
```

## 📝 Pull Request Workflow

1. **Fork** the repo and create a branch from `main`
   ```bash
   git checkout -b feat/your-feature-name
   ```
2. **Make changes** following the code style:
   - TypeScript strict mode
   - Prettier formatting (`npm run format`)
   - ESLint clean (`npm run lint`)
3. **Test** your changes locally
4. **Commit** with conventional commits:
   - `feat: add new feature`
   - `fix: resolve bug X`
   - `docs: update README`
   - `chore: bump deps`
5. **Push** and open a PR with a clear description

## ✅ PR Checklist

- [ ] Code builds without errors (`npm run build`)
- [ ] Linter passes (`npm run lint`)
- [ ] Changes documented in CHANGELOG.md
- [ ] No console.log left in production code
- [ ] Screenshots attached if UI changed

## 🎨 Showcase Submissions

To add your project to the showcase:

1. Edit the **Showcase** table in `README.md`
2. Add a row: `| Site Name | [Demo](url) | [Source](url) |`
3. Open a PR titled `showcase: add <site-name>`

## 💬 Questions?

- Issues: [GitHub Issues](https://github.com/mocasus/web-clone/issues)
- Direct: [Telegram @rubuskap](https://t.me/rubuskap)
