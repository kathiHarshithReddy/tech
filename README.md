# Kathi Harshith Reddy — Portfolio

Cybersecurity & AI Portfolio — Military-grade dark terminal aesthetic.

**Live URL after deployment:** `https://kathiHarshithReddy.github.io/tech`

---

## 🚀 Deploy to GitHub Pages (Free Hosting)

### Step 1 — Create the repo

1. Go to [github.com/new](https://github.com/new)
2. Name it exactly: **`tech`**
3. Set to **Public**
4. Click **Create repository** (don't initialize with anything)

### Step 2 — Upload files

**Option A — GitHub Web UI (easiest):**
1. Open your new `tech` repo
2. Click **"uploading an existing file"**
3. Drag and drop `index.html` and `README.md`
4. Commit message: `Initial portfolio deployment`
5. Click **Commit changes**

**Option B — Git CLI:**
```bash
git init
git add .
git commit -m "Initial portfolio deployment"
git branch -M main
git remote add origin https://github.com/kathiHarshithReddy/tech.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your `tech` repo → **Settings** → **Pages**
2. Under **Source** → select **Deploy from a branch**
3. Branch: **main** | Folder: **/ (root)**
4. Click **Save**

### Step 4 — Your site is live!

Wait ~60 seconds, then visit:
```
https://kathiHarshithReddy.github.io/tech
```

---

## 📁 File Structure

```
tech/
├── index.html     ← Complete portfolio (single file, no build needed)
└── README.md      ← This file
```

No npm, no Node, no build step. Just upload and go.

---

## ✏️ Quick Customization Reference

| What | Where in `index.html` |
|---|---|
| Skill percentages | `skill-fill` `width` values in `#skills` |
| Add a new project | Copy any `.project-card` div in `#projects-grid` |
| Bio text | `.about-text` paragraphs |
| Stats numbers | `.stat-num` spans in `#about` |
| Typewriter roles | `const roles = [...]` in `<script>` |
| Contact links | `.contact-links` section |

---

## 📬 Contact

- **Email:** kathiharshithreddy@gmail.com  
- **GitHub:** [github.com/kathiHarshithReddy](https://github.com/kathiHarshithReddy)  
- **LinkedIn:** [linkedin.com/in/kathi-harshith-reddy](https://www.linkedin.com/in/kathi-harshith-reddy)
# tech
