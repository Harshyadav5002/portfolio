# Harsh - Personal Portfolio

A stunning, production-grade single-file portfolio website built with vanilla HTML, CSS, and JavaScript.

**Live Demo:** [https://your-username.github.io/harsh-portfolio](https://your-username.github.io/harsh-portfolio) (after GitHub Pages setup)

## Features

- **Dark futuristic AI/ML aesthetic** with electric violet (#7c3aed) and neon cyan (#06b6d4) accents
- **Hero with large oval video background** (auto-plays, controls for sound/play, loops twice then stops)
- **GSAP + ScrollTrigger** for smooth, professional animations (staggered entrances, scroll reveals)
- **Interactive particle canvas** in the hero
- **Custom glowing cursor** with hover states
- **Live Web Demo** of the Online Examination System (fully functional timed quiz with scoring)
- **3D tilt effects** on project cards (mouse tracking)
- **Animated skill bars** and count-up statistics
- **Fully responsive** (mobile, tablet, desktop)
- **Accessible** with proper ARIA labels, semantic HTML, and focus styles
- **Production-ready** for GitHub Pages, Netlify, or Vercel

## Getting Started (Local)

```bash
# 1. Clone or download this repo
git clone https://github.com/YOUR_USERNAME/harsh-portfolio.git
cd harsh-portfolio

# 2. Open in browser (or use a local server for best experience)
start index.html

# Recommended: Use a simple server
npx serve .
# or
python -m http.server 8000
```

## Deploy to GitHub (Recommended)

1. Create a **new public repository** on GitHub named `harsh-portfolio` (or your preferred name). **Do not** initialize it with a README.

2. In this folder, run these commands (replace `YOUR_USERNAME`):

```bash
git remote add origin https://github.com/YOUR_USERNAME/harsh-portfolio.git
git branch -M main
git push -u origin main
```

3. Go to your repo on GitHub → **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
   - Save

4. Your site will be live at: `https://YOUR_USERNAME.github.io/harsh-portfolio`

The video (`hero-bg.mp4`) is included in the repo (small enough at ~9MB).

## Tech Stack

- Pure HTML5 + CSS3 (CSS custom properties, glassmorphism, modern layout)
- Vanilla JavaScript (no frameworks)
- GSAP 3 (ScrollTrigger for animations)
- HTML5 `<video>` + Canvas API (particles)
- Fully semantic and accessible

## Customization

Everything is in `index.html` (single file for simplicity). Edit text, colors (in :root), video source, or sections directly.

To replace the hero video:
- Put your new `.mp4` in this folder as `hero-bg.mp4`
- Or update the `<source src="...">` in the HTML

## Project Sections

- **Hero**: Left-aligned intro + large right oval video (auto-play with sound controls)
- **About**: Profile with stats (animated counters) + education + tech badges
- **Skills**: Categorized with progress bars + tags
- **Projects**: 4 featured projects with 3D tilt + live demo
- **Certifications**: Clean cards with badges
- **Contact**: Cards + functional form simulation

## Credits

Built by **Harsh**  
B.Tech Computer Science (AI & ML) | Kanpur Institute of Technology, Batch 2022–2026

Open to internships, collaborations, and entry-level opportunities in AI/ML and web development.

---

**Questions?** Reach out via the contact section in the site or LinkedIn/GitHub links in the footer.
```

## Next Steps for You (to actually push):

1. **Create the GitHub repo first** (public, no auto-README).

2. Run these commands in your terminal (PowerShell or CMD):

```powershell
cd "C:\Users\harsh\Harsh_Portfolio"
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/harsh-portfolio.git
git branch -M main
git push -u origin main
```

(Replace `YOUR_GITHUB_USERNAME` with your actual username.)

If you get auth errors, use a Personal Access Token (classic) with `repo` scope, or set up SSH.

3. After pushing, enable GitHub Pages as described in the README.

The README has been updated with accurate current features (oval video, etc.) and clear deployment steps.

Let me know your GitHub username or if you hit any errors during push—I can help debug the commands! 

If you want the video hosted externally (to keep repo small), I can update the HTML to use a URL instead.