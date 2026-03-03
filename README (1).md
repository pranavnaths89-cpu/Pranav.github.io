# Pranavnath S — Personal Resume Website

A professional, dark-themed personal portfolio/resume website for **Pranavnath S**, law student at SASTRA Deemed University specializing in M&A, Private Equity, and Corporate Advisory.

---

## 📁 File Structure

```
pranavnath-website/
├── index.html      ← Main HTML file (all content)
├── style.css       ← Full CSS stylesheet (dark gold theme)
├── script.js       ← JavaScript (animations, scroll effects)
└── README.md       ← This file
```

---

## 🎨 Design Overview

| Feature | Detail |
|---|---|
| Theme | Dark luxury (deep black + gold) |
| Display Font | Cormorant Garamond (elegant serif) |
| Body Font | DM Sans (clean, modern) |
| Color Palette | `#0c0c0e` bg, `#c9a84c` gold, `#f0ead6` cream |
| Layout | Responsive grid with timeline |

---

## 🚀 How to Deploy

### Option 1 — Open Locally
Simply open `index.html` in any modern browser. All fonts load from Google Fonts (internet required).

### Option 2 — GitHub Pages (Free Hosting)
1. Create a new GitHub repository (e.g., `pranavnath-portfolio`)
2. Upload all three files: `index.html`, `style.css`, `script.js`
3. Go to **Settings → Pages**
4. Set source to **main branch / root**
5. Your site will be live at `https://yourusername.github.io/pranavnath-portfolio`

### Option 3 — Netlify (Free, easiest)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop the entire folder
3. Your site goes live instantly with a public URL

### Option 4 — Vercel
```bash
npm i -g vercel
cd pranavnath-website/
vercel
```

---

## ✏️ How to Edit Content

All content lives in **`index.html`**. Search for the relevant section:

| Section | Search for |
|---|---|
| Name / Contact | `class="hero-content"` |
| Profile Summary | `class="summary-text"` |
| Experience | `class="timeline"` |
| Education | `class="edu-grid"` |
| Research | `class="research-cols"` |
| Mooting | `class="moot-grid"` |

---

## 📱 Responsive Breakpoints

| Screen | Layout |
|---|---|
| Desktop (> 900px) | Full multi-column layout |
| Tablet (600–900px) | 2-column grids, hamburger nav |
| Mobile (< 600px) | Single-column, compact spacing |

---

## 🔧 Customization

**To change accent color** (currently gold `#c9a84c`), edit in `style.css`:
```css
:root {
  --gold: #c9a84c;       /* Main gold */
  --gold-light: #e8c97a; /* Lighter gold */
}
```

**To add a profile photo**, inside `index.html` hero section:
```html
<img src="your-photo.jpg" class="hero-photo" alt="Pranavnath S" />
```

Then add in `style.css`:
```css
.hero-photo {
  width: 160px; height: 160px;
  border-radius: 50%;
  border: 2px solid var(--gold);
  margin-bottom: 2rem;
}
```

---

## 📄 License
Personal use only. Designed for Pranavnath S's professional portfolio.
