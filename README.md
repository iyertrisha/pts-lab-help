# pts-lab-help

Static site for the **Lab Exam — Complete Foolproof Guide** (`complete_lab_exam_guide_v2`).

## What’s in this repo

| File | Purpose |
|------|---------|
| `index.html` | Full guide (single file, embedded CSS) |
| `vercel.json` | Optional legacy URL `/complete_lab_exam_guide_v2.html` → same page |

## Deploy on Vercel

1. Push this repo to GitHub (already configured for `iyertrisha/pts-lab-help`).
2. In [Vercel](https://vercel.com): **Add New Project** → **Import** `iyertrisha/pts-lab-help`.
3. **Framework Preset:** *Other* (or leave auto-detect; static HTML needs no build).
4. **Root Directory:** `.` (repository root contains `index.html`).
5. **Build Command:** leave empty. **Output:** default (Vercel serves static files from the project root).
6. Deploy. The site root `/` serves `index.html`.

## Checklist (maintainer)

- [ ] Only `index.html`, `vercel.json`, `README.md`, `.gitignore` tracked — no lab manuals or binaries.
- [ ] After deploy, open production URL and confirm the guide loads and styles render (Google Fonts load over HTTPS).
