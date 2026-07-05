# 🌿 BioLab 10 — Control & Coordination in Plants

An interactive, cinematic CBSE Class 10 (NCERT) biology simulation covering tropisms, nastic
movements, plant hormones, a virtual lab, quizzes, flashcards, exam practice and more.

**Developer:** A. Kritthik Shriraman

---

## 🚀 Host it on GitHub Pages (automatic — recommended)

This repo includes a ready-made GitHub Actions workflow that builds and deploys the site for you.

1. **Create a GitHub repository** and push this project to it:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repo → **Settings** → **Pages**.
   - Under **Build and deployment → Source**, choose **GitHub Actions**.

3. That's it. Every push to `main` (or `master`) automatically builds and publishes the site.
   The live URL appears in **Settings → Pages** and in the **Actions** run summary, usually:
   ```
   https://<your-username>.github.io/<your-repo>/
   ```

> The app is built as a **single self-contained `index.html`** (all CSS/JS inlined), so it works at
> any URL — root domain, project subpath, or a custom domain — with no path configuration needed.

---

## 🖐️ Manual deploy (alternative)

If you prefer not to use Actions:

```bash
npm install
npm run build          # generates dist/index.html
```

Then either:

- **Option A — `docs/` folder:** copy `dist/` into a `docs/` folder, commit it, and in
  **Settings → Pages** set Source to **Deploy from a branch → main → /docs**.
- **Option B — `gh-pages` branch:** push the contents of `dist/` to a `gh-pages` branch and point
  Pages at that branch.

Because the build is a single file, you can also just drag `dist/index.html` onto Netlify, Vercel,
Cloudflare Pages, or open it directly in a browser.

---

## 🧑‍💻 Local development

```bash
npm install
npm run dev       # start the dev server
npm run build     # production build → dist/
npm run preview   # preview the production build locally
```

---

## 📚 What's inside

- **Interactive Simulations** — Phototropism, Geotropism, Hydrotropism, Thigmotropism, Mimosa,
  Hormone Lab, Cellular Zoom
- **Virtual Laboratory** — full NCERT experiments (aim, materials, procedure, observation, conclusion)
- **Learn Concepts** — 11 NCERT topics with keywords, exam tips, common mistakes, memory tricks & FAQs
- **Chapter Explorer**, **Quiz Arena**, **Challenge Missions**, **Flashcards**, **Exam Practice**,
  **Rapid Revision**, and a **Progress Dashboard**

All content is verified against the CBSE Class 10 NCERT Science textbook.

---

## 🛠️ Tech

React · Vite · TypeScript · Tailwind CSS · single-file build
