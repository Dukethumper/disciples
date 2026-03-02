# Disciples — Motivational Archetypes

A 238-question personality assessment mapping your motivational core across 12 archetypes.

## 🚀 Live Site

Once deployed, your site will be available at:
`https://<your-username>.github.io/disciples/`

---

## 📦 Deploy to GitHub Pages (step by step)

### 1. Create the repository

1. Go to [github.com](https://github.com) and sign in
2. Click **+** → **New repository**
3. Name it `disciples` (or anything you like)
4. Set visibility to **Public**
5. Leave "Initialize with README" **unchecked**
6. Click **Create repository**

### 2. Upload the file

**Option A — via the GitHub website (easiest):**
1. On your new repo page, click **Add file** → **Upload files**
2. Drag and drop `index.html` into the upload area
3. Click **Commit changes**

**Option B — via Git (command line):**
```bash
git init
git add index.html
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/disciples.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Set branch to `main`, folder to `/ (root)`
4. Click **Save**
5. Wait ~60 seconds, then visit `https://<your-username>.github.io/disciples/`

---

## 📁 File Structure

```
disciples/
└── index.html      ← The entire app (self-contained, no dependencies)
└── README.md       ← This file
```

Everything — questions, scoring logic, styles, and archetype descriptions — lives inside `index.html`. No build step, no server, no packages required.

---

## ✏️ Making Changes

Edit `index.html` directly. After saving, commit and push — GitHub Pages will redeploy automatically within a minute.

```bash
git add index.html
git commit -m "Update questions"
git push
```
