# Pragna Chandanamudi — Portfolio

Personal portfolio website for **Pragna Chandanamudi**, Analytics AVP specializing in Financial Crime, AI/ML, and Data Engineering.

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon (top right) → **New repository**
3. Name it exactly: `pragna-portfolio` *(or any name you like)*
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the Files

**Option A — GitHub Website (easiest, no coding needed):**
1. On your new repo page, click **"uploading an existing file"**
2. Drag and drop the `index.html` file from this folder
3. Scroll down → click **"Commit changes"**

**Option B — Git command line:**
```bash
git init
git add .
git commit -m "Initial portfolio deploy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/pragna-portfolio.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. In your repo, click **Settings** (top menu)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**

### Step 4 — Your Live URL

After ~2 minutes your site will be live at:
```
https://YOUR_GITHUB_USERNAME.github.io/pragna-portfolio/
```

---

## 🌐 Custom Domain (Optional)

If you have a domain like `pragna.dev`:

1. In GitHub Pages settings → add your domain under **Custom domain**
2. At your domain registrar, add a CNAME record:
   - Name: `www`
   - Value: `YOUR_USERNAME.github.io`

---

## 📁 File Structure

```
pragna-portfolio/
├── index.html      ← Your entire portfolio (self-contained)
└── README.md       ← This file
```

Everything — styles, scripts, fonts, your photo, and music — is embedded directly in `index.html`. No external dependencies to manage.

---

## ✨ Features

- Animated hero with spinning gradient photo frame
- Energetic Web Audio music player (128 BPM)
- Scroll-reveal animations & custom cursor
- Skills grid with progress bars
- Experience timeline
- Robotics & data processing projects
- Publications with full paper modal
- Mobile responsive

---

Built with pure HTML, CSS & JavaScript. No frameworks, no build step, no dependencies.
