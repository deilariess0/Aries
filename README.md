# Deil Aries Santos — Portfolio Website

A personal IT portfolio website built with HTML, CSS, and JavaScript.

## 📁 Files
- `index.html` — Main page
- `style.css` — All styles
- `script.js` — Interactivity (theme toggle, scroll effects, form)
- `profile.jpg` — **Add your photo here** (name it exactly `profile.jpg`)
- `resume.pdf` — **Add your resume here** (name it exactly `resume.pdf`)

---

## 🚀 How to Deploy on GitHub Pages

### Step 1 — Create a GitHub Account
Go to https://github.com and sign up (if you don't have an account).

### Step 2 — Create a New Repository
1. Click the **+** icon → **New repository**
2. Name it: `portfolio` (or `yourusername.github.io` for a cleaner URL)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload Your Files
**Option A — Upload via browser (easiest):**
1. Inside your new repo, click **Add file** → **Upload files**
2. Drag and drop all files: `index.html`, `style.css`, `script.js`, `profile.jpg`, `resume.pdf`
3. Click **Commit changes**

**Option B — Using Git (recommended):**
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOURUSERNAME/portfolio.git
git push -u origin main
```

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Branch**, select `main` → folder `/root`
3. Click **Save**
4. Wait ~1 minute, then visit: `https://yourusername.github.io/portfolio`

---

## ⚡ How to Deploy on Vercel (even better)

Vercel gives you a faster, professional URL like `yourname.vercel.app`.

### Step 1 — Push to GitHub first (follow steps above)

### Step 2 — Connect to Vercel
1. Go to https://vercel.com and click **Sign Up with GitHub**
2. Click **Add New Project**
3. Find your `portfolio` repo and click **Import**
4. Leave all settings as default (Framework: Other)
5. Click **Deploy**

### Step 3 — Get your live URL
After ~30 seconds, Vercel gives you a URL like:
`https://portfolio-deilaries.vercel.app`

### Step 4 — Custom Domain (optional)
In Vercel → your project → **Settings** → **Domains**
Add your own domain (e.g., `deilaries.com`) if you have one.

---

## 📸 Adding Your Photo & Resume

1. **Profile photo:** Save your photo as `profile.jpg` and put it in the same folder as `index.html`
2. **Resume:** Save your resume as `resume.pdf` in the same folder

Then re-upload/push to GitHub and Vercel will auto-update.

---

## ✏️ How to Edit Content

All text content is in `index.html`. Search for these to update:
- `Deil Aries Santos` — Your name
- `deilariessantos@gmail.com` — Your email
- `+63 968 249 2564` — Your phone
- Skills percentages → look for `style="--pct:90%"` and change the number
- Experience → find `Bucket Economics` and `DMCI` sections
- Projects → find `project-card` sections

---

## 🎨 Changing Colors

In `style.css`, find the `:root` block at the top:
```css
--purple: #7c5cbf;        /* Main accent color */
--purple-light: #9b79e0;  /* Lighter accent */
```
Change these hex values to any color you like!
