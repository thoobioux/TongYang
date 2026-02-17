# Tong Yang – Portfolio

## How to Deploy to GitHub Pages (Step by Step)

### Step 1: Create a GitHub Account
Go to https://github.com and sign up for a free account if you don't have one.

### Step 2: Create a New Repository
1. Click the **+** icon in the top right corner
2. Select **New repository**
3. Name it exactly: `tong-yang-portfolio` (or any name you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 3: Upload Your Files
1. On your new repo page, click **uploading an existing file**
2. Drag and drop ALL the files and folders from this project:
   - `src/` folder
   - `.github/` folder
   - `index.html`
   - `package.json`
   - `vite.config.js`
   - `README.md`
3. Scroll down and click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to your repo **Settings** tab
2. Click **Pages** in the left sidebar
3. Under **Source**, select **GitHub Actions**
4. Click **Save**

### Step 5: Wait for Deployment
1. Click the **Actions** tab in your repo
2. You'll see a workflow running called "Deploy to GitHub Pages"
3. Wait 2–3 minutes for it to complete (green checkmark = done)

### Step 6: View Your Live Site
Your site will be live at:
**https://YOUR-GITHUB-USERNAME.github.io/tong-yang-portfolio/**

---

## Making Updates Later
Whenever you want to update the site:
1. Edit the files
2. Upload the changed files to GitHub (same drag and drop process)
3. The site will automatically rebuild and redeploy within a few minutes

---

## Running Locally (Optional)
If you want to preview the site on your computer before uploading:
1. Install Node.js from https://nodejs.org
2. Open Terminal and navigate to this folder
3. Run: `npm install`
4. Run: `npm run dev`
5. Open http://localhost:5173 in your browser
