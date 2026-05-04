# 🌐 Shruti Kumari — Portfolio Website

[![Live Site](https://img.shields.io/badge/🚀%20Live%20Site-shrutisurya108.github.io-38bdf8?style=for-the-badge)](https://shrutisurya108.github.io)
[![HTML](https://img.shields.io/badge/HTML5-Single%20File-E34F26?style=for-the-badge&logo=html5&logoColor=white)](index.html)
[![License](https://img.shields.io/badge/License-MIT-4ade80?style=for-the-badge)](LICENSE)

> Personal portfolio website for **Shruti Kumari** — Data Scientist | AI/ML Explorer  
> Built as a single-file, zero-dependency HTML/CSS/JS site hosted on GitHub Pages.

---

## ✨ Features

- 🌗 **Dark / Light theme toggle** — auto-detects system preference
- 🖱️ **Custom animated cursor** with hover interactions
- 🔮 **Particle network background** (canvas-based, animated)
- 📜 **Scroll-reveal animations** on all sections
- 💬 **Auto-rotating quotes carousel** with manual controls
- 📱 **Fully responsive** — mobile, tablet, desktop
- ⚡ **Zero dependencies** — no frameworks, no build step; just one HTML file
- ✏️ **Placeholder slots** for 2 additional projects ready to fill in

---

## 🗂️ Site Sections

| Section | Description |
|---|---|
| **Hero** | Name, title, animated stats, floating tech tags |
| **The Story So Far** | Bio, live code card, portfolio + social links |
| **Things I'm Good At** | 8 capability cards with tech tags |
| **Where I've Shipped** | Timeline-based work experience with impact badges |
| **The Lab** | 4 real + 2 placeholder project cards with metrics |
| **The Toolkit** | Full skill grid organized by category with HOT badges |
| **Data Minds Speak** | Auto-rotating developer quotes carousel |
| **Contact** | Social links + contact info card |

---

## 🚀 Deployment (GitHub Pages)

### Step 1 — Create the repo
```
Repository name: shrutisurya108.github.io
Visibility: Public
```
> The repo name **must** match your GitHub username exactly for user-level GitHub Pages.

### Step 2 — Add the file
```bash
git clone https://github.com/shrutisurya108/shrutisurya108.github.io
cd shrutisurya108.github.io
# Copy index.html into this folder
git add index.html
git commit -m "🚀 Launch portfolio website"
git push origin main
```

### Step 3 — Enable GitHub Pages
1. Go to **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `root`
4. Save → Your site is live at `https://shrutisurya108.github.io` 🎉

---

## ✏️ Customization Checklist

### 🔴 Required — Do these first

- [ ] **Add your photo**: Find `avatar-placeholder` div in `index.html` and replace with:
  ```html
  <img class="avatar-img" src="your-photo.jpg" alt="Shruti Kumari"/>
  ```
  Upload your photo to the same repo folder.

- [ ] **Portfolio link**: Search for `your-portfolio-link-here.com` — replace all instances with your actual URL (or remove those buttons if not ready).

- [ ] **Resume link**: Find the `<!-- 🔗 Replace # with your actual portfolio/resume link -->` comment and replace `href="#"` with your resume URL (Google Drive, Dropbox, etc.)

- [ ] **GitHub username in links**: Update `https://github.com/shrutisurya108` if your username differs.

- [ ] **Kaggle link**: Replace the `href="#"` on the Kaggle social button with your Kaggle profile URL.

### 🟡 Projects — Fill in placeholder cards

Each placeholder card is clearly marked with `<!-- ✏️ PLACEHOLDER PROJECT 5 -->` comments. For each:
1. Update the `project-title` div
2. Update the `project-desc` div  
3. Update `metric-val` and `metric-lbl` values
4. Update `stack-pill` spans with your actual tech stack
5. Replace `href="#"` on GitHub and demo links
6. Remove the `<div class="placeholder-tag">Coming Soon</div>` line
7. Change the `project-icon` emoji to something fitting

### 🟢 Optional enhancements

- **Add more projects**: Copy any `project-card` block and paste inside `.projects-grid`
- **Add social links**: Duplicate a `.social-link` in the Contact section (Twitter/X, Medium, etc.)
- **Update quotes**: Add your own to the `#quote-track` div — copy any `.quote-slide` block
- **Change color accent**: Edit `--accent` in the `:root` CSS block (default: `#38bdf8`)
- **Update stats**: Hero stats are hardcoded — update numbers in the `.hero-stats` section

---

## 🗂️ File Structure

```
shrutisurya108.github.io/
│
├── index.html          # ← The entire site (single file)
├── your-photo.jpg      # ← Add your photo here
└── README.md           # ← This file
```

---

## 🎨 Design Decisions

| Choice | Reason |
|---|---|
| **Single HTML file** | Zero build tooling, instant GitHub Pages deploy |
| **DM Mono + Syne + Instrument Serif** | Technical precision + editorial impact |
| **Dark default, light toggle** | ML/dev audiences prefer dark; system-aware fallback |
| **Canvas particles** | Adds depth without heavy libraries |
| **No frameworks** | Loads instantly, works everywhere, no dependencies to break |

---

## 📬 Contact

**Shruti Kumari**  
📧 shrutikumari4876@gmail.com  
📞 +1 (716) 232-0253  
🔗 [LinkedIn](https://www.linkedin.com/in/shrutikumari108/)  
🐙 [GitHub](https://github.com/shrutisurya108)

---

<div align="center">
  <sub>Built with ❤️ and way too much coffee &nbsp;·&nbsp; © 2026 Shruti Kumari</sub>
</div>
