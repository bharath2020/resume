# GitHub Pages Resume

This repository hosts Bharath Booshan's resume using GitHub Pages.

## 🚀 Deployment Instructions

### Option 1: Deploy to github.io (Recommended)

1. **Create a new GitHub repository**
   - Go to https://github.com/new
   - Name it `[your-username].github.io` (e.g., `bharath2020.github.io`)
   - Make it public
   - Don't initialize with README

2. **Push this code to GitHub**
   ```bash
   cd github-resume
   git init
   git add .
   git commit -m "Initial resume commit"
   git branch -M main
   git remote add origin https://github.com/[your-username]/[your-username].github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Click Save

4. **Access your resume**
   - Your resume will be live at: `https://[your-username].github.io`
   - It may take a few minutes to deploy

### Option 2: Deploy to a project repository

1. **Create a new GitHub repository**
   - Go to https://github.com/new
   - Name it `resume` or any name you prefer
   - Make it public

2. **Push this code**
   ```bash
   cd github-resume
   git init
   git add .
   git commit -m "Initial resume commit"
   git branch -M main
   git remote add origin https://github.com/[your-username]/resume.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Same steps as Option 1

4. **Access your resume**
   - Your resume will be live at: `https://[your-username].github.io/resume`

## 📝 Customization

### Change Theme
Edit `_config.yml` and change the theme. Popular options:
- `jekyll-theme-minimal` (current)
- `jekyll-theme-cayman`
- `jekyll-theme-slate`
- `jekyll-theme-architect`
- `jekyll-theme-modernist`

### Update Content
Edit `index.md` to update your resume content.

## 🔄 Updates

After making changes:
```bash
git add .
git commit -m "Update resume"
git push
```

GitHub Pages will automatically rebuild and deploy your changes.