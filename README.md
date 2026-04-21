# 🚀 Ritik Raj — Portfolio Website

A premium 3D animated portfolio website with particle effects, aurora backgrounds, and smooth animations.

---

## 📁 Project Structure

```
ritik-portfolio/
│
├── index.html                  ← Main portfolio (single-file, zero dependencies)
├── netlify.toml                ← Netlify deployment config
├── vercel.json                 ← Vercel deployment config
├── .gitignore
│
├── docs/
│   └── Ritik_Raj_ATS_Resume.docx   ← ATS-optimized resume
│
└── .github/
    └── workflows/
        └── deploy.yml          ← GitHub Actions auto-deploy
```

---

## ⚡ Deploy in 60 Seconds

### ✅ Option 1 — Netlify (Recommended, FREE)

1. Go to **https://app.netlify.com**
2. Click **"Add new site" → "Deploy manually"**
3. Drag and drop the entire `ritik-portfolio/` folder
4. ✅ Live in 30 seconds at a `*.netlify.app` URL

**Custom domain (optional):**
- Go to Site Settings → Domain management → Add custom domain
- e.g. `ritikraj.dev`

---

### ✅ Option 2 — Vercel (FREE)

```bash
# Step 1: Install Vercel CLI
npm install -g vercel

# Step 2: Go into the project folder
cd ritik-portfolio

# Step 3: Deploy
vercel

# Follow the prompts — done!
```

Or use the web UI:
1. Go to **https://vercel.com/new**
2. Import from GitHub or upload folder
3. Click Deploy

---

### ✅ Option 3 — GitHub Pages (FREE, auto-deploys on push)

```bash
# Step 1: Create a new GitHub repo (e.g. "portfolio")
# Go to https://github.com/new

# Step 2: Push this folder to the repo
cd ritik-portfolio
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/RitikRaj0105/portfolio.git
git push -u origin main

# Step 3: GitHub Actions automatically deploys to:
# https://ritikraj0105.github.io/portfolio/
```

---

### ✅ Option 4 — Local Preview (instant)

Just open `index.html` in any browser:

```bash
# macOS / Linux
open index.html

# Windows
start index.html

# Or use VS Code Live Server extension
```

---

## 🌐 Custom Domain Setup

After deploying to Netlify or Vercel:

| Registrar | Price/yr | Where to buy |
|-----------|----------|--------------|
| Namecheap | ~₹800    | namecheap.com |
| GoDaddy   | ~₹999    | godaddy.com |
| Google Domains | ~₹1,200 | domains.google |

**Recommended domain:** `ritikraj.dev` or `ritikraj.in`

---

## ✏️ How to Customize

All content is in `index.html`. Search for these sections to edit:

| What to change | Search for |
|---------------|------------|
| Your name/title | `RITIK RAJ` |
| Contact email | `rraj824233@gmail.com` |
| GitHub link | `RitikRaj0105` |
| LinkedIn link | `ritik-raj-771112224` |
| Phone | `8102560920` |
| Projects | `project-card` |
| Skills | `skill-items` |
| Experience | `exp-item` |

---

## 📄 ATS Resume

The file `docs/Ritik_Raj_ATS_Resume.docx` is your ATS-optimized resume.

**Tips:**
- Upload to job portals as-is (Word format, not PDF, for max ATS parsing)
- For human review, export as PDF from Microsoft Word or Google Docs
- Keep updating it as you gain new experience

---

## 🛠 Tech Stack

- Pure HTML + CSS + JavaScript (zero frameworks, zero dependencies)
- Three.js-style canvas particles (custom built)
- Google Fonts: Syne + Space Mono
- Fully responsive, works on mobile

---

## 📬 Contact

**Ritik Raj** — rraj824233@gmail.com — IIT Patna
