# Build Verification Log

This document is the auto-generated proof that this repository builds cleanly on a fresh environment.

**Last verified:** 2026-06-30 (UTC)
**Verifier:** mocasus (manual smoke test on Debian 12 VPS)

---

## Environment

```
Host:     Debian 12 (Linux 6.1.0-47-cloud-amd64)
Node:     v24.18.0
npm:      11.x (bundled with Node 24)
RAM:      945 MB
Status:   clean clone, no cache
```

## Steps

### 1. Fresh clone

```bash
git clone https://github.com/mocasus/web-clone.git
cd web-clone
```

### 2. Install dependencies

```bash
$ npm install

added 625 packages, and audited 626 packages in 19s
236 packages are looking for funding
12 vulnerabilities (1 low, 7 moderate, 4 high)
```

✅ Install completes in ~20s with zero errors.

### 3. Production build

```bash
$ npm run build

> web-clone@1.0.0 build
> next build

▲ Next.js 16.2.1 (Turbopack)

  Creating an optimized production build ...
✓ Compiled successfully in 6.3s
  Running TypeScript ...
  Finished TypeScript in 4.0s
  Collecting page data using 1 worker ...
✓ Generating static pages using 1 worker (4/4) in 208ms
  Finalizing page optimization ...

Route (app)
┌ ○ /
└ ○ /_not-found

○  (Static)  prerendered as static content
```

✅ **Build completes successfully — exit code 0.**

- Compile time: **6.3s** (Turbopack)
- TypeScript: **4.0s** (no type errors)
- Static pages: **4/4 generated in 208ms**
- Routes: `/` and `/_not-found` both pre-rendered as static

### 4. Dev server (optional)

```bash
$ npm run dev
▲ Next.js 16.2.1 (Turbopack)
- Local:        http://localhost:3000
- Ready in 1.2s
```

---

## Summary

| Check | Result |
|---|---|
| `npm install` clean | ✅ |
| `npm run build` exit 0 | ✅ |
| TypeScript type check | ✅ |
| Static page generation | ✅ 4/4 |
| Compile time | 6.3s |
| Dev server starts | ✅ |

The template is verified working on Node 24+ with the published `package.json` dependencies. Any failure to reproduce these results on a fresh clone is a bug — please [open an issue](https://github.com/mocasus/web-clone/issues).
