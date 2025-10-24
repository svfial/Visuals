# Visuals
physics and engineering visuals for easier understanding


This repo is a simple static site for visual engineering explainers.  
Site files are in the root and `posts/`. No build tools required — GitHub Pages will serve the files.

## Quick files
- `index.html` — homepage
- `styles.css` — styles
- `posts/post-bridge.html` — bridges post
- `posts/post-hookes.html` — Hooke's law post
- `posts/post-rc.html` — RC circuits post

## How to deploy
1. create repo named `svfial.github.io`
2. add these files (via web UI or git)
3. enable GitHub Pages (Settings → Pages → Branch: main / root)
4. site will be at https://svfial.github.io

## Local git commands (recommended)
```bash
# create local folder
mkdir svfial-site
cd svfial-site

# init and connect to repo (replace with your origin url)
git init
git remote add origin https://github.com/svfial/svfial.github.io.git

# copy files into folder, then:
git add .
git commit -m "initial site"
git branch -M main
git push -u origin main
