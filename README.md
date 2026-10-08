# 🚀 Modern & Minimalist Portfolio Website

A sleek, ultra-fast, responsive portfolio website built with modern HTML5, CSS3 (Custom Properties & Bento Grid), and Vanilla JavaScript. Specially tailored for an **Informatics Engineering & Software Developer** profile.

---

## ✨ Features

- **Modern & Minimalist Design**: Clean aesthetics inspired by Linear, Apple, and Vercel.
- **Dark & Light Mode**: Instant toggle with auto-detection of system preference and `localStorage` persistence.
- **Zero Dependencies / No Build Tools Required**: Works immediately right out of the box in any browser.
- **Responsive Layout**: Pixel-perfect on mobile, tablet, laptop, and ultra-wide displays.
- **Bento Grid Highlights**: Visual overview of engineering foundations, key metrics, and core philosophies.
- **Interactive Projects Filter**: Dynamic category filtering (All, Full-Stack, Web Apps, Systems & AI).
- **Working Interactive Elements**:
  - One-click copy email button with toast feedback.
  - Interactive contact form with input validation.
  - Smooth scroll spy with navbar highlights.
  - Mobile slide-out navigation menu.

---

## 📁 Project Structure

```
Portofolio/
├── index.html        # Main HTML structure with semantic sections
├── css/
│   └── style.css     # Theme variables, responsive styles & animations
├── js/
│   └── main.js       # Dark/light theme, filters, toasts & interactions
└── README.md         # Documentation & customization guide
```

---

## ⚡ How to Run & Preview

1. Navigate to this folder: `c:\Users\Fiy\Desktop\Informatics Eng\Portofolio`
2. **Double-click `index.html`** to open it directly in your favorite browser (Chrome, Edge, Firefox, Brave, Safari).
3. That's it! No `npm install`, Node.js, or server setup is required.

---

## 🛠️ Personalization & Customization

### 1. Change Your Name & Titles
Open [index.html](file:///c:/Users/Fiy/Desktop/Informatics%20Eng/Portofolio/index.html) and search for:
- Replace `Fiy` with your preferred display name or full name.
- Update the hero headline and subtitle to match your specialty.

### 2. Update Social Links & Email
In [index.html](file:///c:/Users/Fiy/Desktop/Informatics%20Eng/Portofolio/index.html), search for the contact section and hero links:
- Change `fiy.informatics@gmail.com` to your real email.
- Change `https://github.com` and `https://linkedin.com` to your respective profile URLs.

### 3. Add or Modify Projects
Find the `<section id="projects">` in [index.html](file:///c:/Users/Fiy/Desktop/Informatics%20Eng/Portofolio/index.html). Each `<article class="project-card">` can be customized with:
- `data-category`: Choose between `fullstack`, `web`, or `systems`.
- Project title, description, and tech stack tags (`<span>`).
- Links to your GitHub repositories or live project demos.

### 4. Custom Colors & Themes
You can adjust the accent colors in [css/style.css](file:///c:/Users/Fiy/Desktop/Informatics%20Eng/Portofolio/css/style.css) under `:root`:
```css
--accent-primary: #38bdf8;   /* Change to your favorite accent color */
--accent-secondary: #818cf8;
```

---

## 🌐 Free 1-Click Deployment

### Option A: GitHub Pages (Recommended)
1. Initialize git and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio release"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
2. On GitHub, go to **Settings** > **Pages**.
3. Under **Branch**, select `main` and root `/`, then click **Save**.
4. Your website will be live at `https://<your-username>.github.io/<your-repo-name>/`!

### Option B: Vercel / Netlify
1. Go to [vercel.com](https://vercel.com) or [netlify.com](https://netlify.com).
2. Drag and drop the `Portofolio` folder directly into their dashboard to deploy in 10 seconds.
