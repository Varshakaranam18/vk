# Deployment Instructions

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `VK_PORTFOLIO`
3. Description: "My personal portfolio website"
4. Set to **Public** (required for free GitHub Pages)
5. **DO NOT** initialize with README, .gitignore, or license
6. Click "Create repository"

## Step 2: Push to GitHub

After creating the repository, run these commands in your terminal:

```bash
cd /Users/varshakaranam/VK_PORTFOLIO

# Add remote (replace with your actual repository URL)
git remote add origin https://github.com/Varshakaranam18/VK_PORTFOLIO.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

Your portfolio will be live at:
**https://varshakaranam18.github.io/VK_PORTFOLIO/**

## Future Updates

To update your portfolio:

```bash
git add .
git commit -m "Update portfolio content"
git push
```

Changes will be live within a few minutes!

