# CODE — Official Website
> // build · ship · repeat

**c137techmedia@gmail.com**

---

## File Structure

```
code-site/
├── index.html          ← Home / Landing page
├── services.html       ← Services page
├── products.html       ← Tech products page
├── creative.html       ← Design & advertising page
├── photography.html    ← Photography page
├── about.html          ← About page
├── contact.html        ← Contact page
├── assets/
│   ├── css/
│   │   └── styles.css  ← All shared styles
│   └── js/
│       └── main.js     ← Theme, nav, animations
└── README.md
```

---

## Deploying to GitHub Pages

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up if you don't have an account.

### Step 2 — Create a new repository
1. Click the **+** icon → **New repository**
2. Name it: `code-site` (or `your-username.github.io` for a root domain)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
**Option A — Drag and drop (easiest):**
1. Open your new repo on GitHub
2. Click **uploading an existing file**
3. Drag the entire `code-site/` folder contents into the upload area
4. Make sure the folder structure is preserved (`assets/css/`, `assets/js/`)
5. Click **Commit changes**

**Option B — GitHub Desktop (recommended):**
1. Download [GitHub Desktop](https://desktop.github.com)
2. Clone your new repo locally
3. Copy all files from `code-site/` into the cloned folder
4. Commit and push

**Option C — Git CLI:**
```bash
cd code-site
git init
git add .
git commit -m "initial deploy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/code-site.git
git push -u origin main
```

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Branch: **main** / Folder: **/ (root)**
4. Click **Save**

### Step 5 — Your site is live
After about 60 seconds your site will be at:
```
https://YOUR_USERNAME.github.io/code-site/
```

---

## Custom Domain (optional)
If you own a domain (e.g. `codeworks.co.zw`):
1. In GitHub Pages settings, enter your domain under **Custom domain**
2. At your domain registrar, add a CNAME record pointing to `YOUR_USERNAME.github.io`

---

## Making Updates
Edit any HTML file locally, then re-upload or push via Git. Changes go live within 30 seconds.

---

*// CODE · c137techmedia@gmail.com · +263 77 883 6177*
