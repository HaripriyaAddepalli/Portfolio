# 🌐 Personal Portfolio Website

**Modern, Interactive Developer Portfolio | HTML + CSS + JavaScript + 3D Visualization**

[![HTML5](https://img.shields.io/badge/HTML5-orange?style=flat-square&logo=html5)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-blue?style=flat-square&logo=css3)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat-square&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=flat-square&logo=vercel)](https://vercel.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

**[🌐 Live Website](https://portfolio-lime-sigma-56.vercel.app/)** | **[📄 View Source](#project-structure)** | **[🎨 Design System](#design-system)**

---

## 📸 Overview

A stunning, fully responsive personal portfolio website showcasing projects, skills, and experience. Features a modern design with elegant purple/teal color scheme, smooth animations, and an interactive 3D rotating globe visualization.

**Perfect for:** Developers, designers, freelancers, students

---

## ✨ Key Features

- ✅ **Responsive Design** — Perfect on desktop, tablet, and mobile
- ✅ **Smooth Animations** — Fade-up animations, scroll effects
- ✅ **3D Globe Visualization** — Rotating particle globe in hero section
- ✅ **Project Showcase** — 6+ featured projects with tech tags
- ✅ **Skills Display** — Organized by category with proficiency bars
- ✅ **Interactive Accordion** — Expandable experience timeline
- ✅ **Live Links** — Direct links to deployed projects
- ✅ **Dark Theme** — Easy on the eyes, modern aesthetic
- ✅ **Optimized Performance** — Fast load times, <100KB
- ✅ **SEO Ready** — Meta tags, proper headings

---

## 🎨 Design System

### Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Deep Navy | `#0a0a14` | Background |
| Surface | `#0d0d18` | Card backgrounds |
| Purple | `#8b5cf6` | Primary accent |
| Teal | `#2dd4bf` | Secondary accent |
| Beige | `#e2d4f0` | Text accent |
| Text | `#ede8f5` | Primary text |

### Typography

- **Headings:** Inter Bold (900) / Inter Bold (800)
- **Body:** Inter Regular (400) / Inter Medium (500)
- **Code:** Fira Code (400/500)

### Spacing System

- Base unit: 8px
- Padding: 48px (desktop), 20px (mobile)
- Gap: 12px-64px (contextual)

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Markup** | HTML5 (semantic) |
| **Styling** | CSS3 (custom properties, flexbox, grid) |
| **Interactivity** | Vanilla JavaScript (ES6+) |
| **3D Graphics** | HTML5 Canvas + WebGL |
| **Animation** | CSS keyframes + JS |
| **Fonts** | Google Fonts (Inter, Fira Code) |
| **Deployment** | Vercel |
| **Version Control** | GitHub |

---

## 🚀 Quick Start

### View Online
Simply visit: **[portfolio-lime-sigma-56.vercel.app](https://portfolio-lime-sigma-56.vercel.app/)**

### Run Locally

1. **Clone repository**
```bash
git clone https://github.com/HaripriyaAddepalli/Portfolio.git
cd Portfolio
```

2. **Start local server**
```bash
# Using Python
python -m http.server 8000

# Or using Node.js
npx http-server

# Or using VS Code
# Install "Live Server" extension and right-click index.html → "Open with Live Server"
```

3. **Open in browser**
```
http://localhost:8000
```

---

## 📋 Sections

### 1. **Hero Section**
- Animated name and typewriter effect
- Professional bio
- CTA buttons (View Work / Get in Touch)
- 3D rotating globe animation
- Scroll hint

### 2. **About Section**
- Professional summary
- Stats cards (6+ internships, 20+ certs, 8+ projects)
- Current role badge

### 3. **Experience Timeline**
- Interactive expandable cards
- 6 internship entries
- Company, role, duration, key achievements
- Smooth animations

### 4. **Skills Section**
- Proficiency bars (Python, ML, React, etc.)
- Skills organized by category
- Hover effects and smooth animations

### 5. **Projects Showcase**
- Grid layout (responsive)
- 6+ featured projects
- Tech tags for each project
- Live demo buttons with links
- Hover animations

### 6. **Certifications**
- 20+ certifications displayed
- Issuer and date
- Icon-based visual design

### 7. **Education**
- Degree, institution, duration
- CGPA and activities

### 8. **Contact Section**
- Professional tagline
- Email contact
- Social links (LinkedIn, GitHub, Email)
- Icon-based buttons

### 9. **Footer**
- Copyright info
- Back to top link

---

## 🎯 Performance

| Metric | Value |
|--------|-------|
| **Page Load** | <1 second |
| **File Size** | <100KB (uncompressed) |
| **Lighthouse Score** | 95+ |
| **Mobile Friendly** | ✅ 100% |
| **Accessibility** | WCAG 2.1 AA |

---

## 📱 Responsive Breakpoints

```css
/* Mobile: < 768px */
- Single column layout
- Reduced padding (20px)
- Stacked sections

/* Tablet: 768px - 1024px */
- 2-column grids
- Medium padding (32px)

/* Desktop: > 1024px */
- Multi-column layouts
- Full padding (48px)
- Hover effects enabled
```

---

## 🎨 Animations

### Entrance Animations
- **Fade-up:** Sections fade in as you scroll
- **Typewriter:** Name types out on load
- **Bounce:** Hero badge pulses

### Interactive Animations
- **Hover effects:** Cards lift and glow
- **Accordion:** Experience items expand/collapse
- **Skill bars:** Fill on scroll visibility
- **3D rotation:** Globe spins smoothly

### CSS Animations
```css
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(22px); }
  to { opacity: 1; transform: translateY(0); }
}
```

---

## 📚 Project Structure

```
Portfolio/
├── index.html           # Main HTML file
├── style.css           # (embedded in HTML)
├── script.js           # (embedded in HTML)
├── assets/
│   ├── images/
│   ├── favicons/
│   └── fonts/
└── README.md
```

**Note:** All CSS and JavaScript are embedded in `index.html` for simplicity and performance.

---

## 🔧 Customization

### Update Personal Info

Edit these in `index.html`:

```html
<!-- Name -->
<h1 class="hero-name">Your Name<br><span class="dim">Here</span></h1>

<!-- Bio -->
<p class="hero-bio">Your professional summary...</p>

<!-- Email -->
<a href="mailto:your-email@example.com">your-email@example.com</a>

<!-- Links -->
<a href="https://linkedin.com/in/your-profile/">LinkedIn</a>
```

### Modify Color Scheme

Edit CSS variables:

```css
:root {
  --purple: #8b5cf6;      /* Change primary color */
  --teal: #2dd4bf;        /* Change secondary color */
  --bg: #0a0a14;          /* Change background */
  --text: #ede8f5;        /* Change text color */
}
```

### Add/Remove Sections

Each section is a `<section>` block. Simply copy/paste and modify content.

---

## 🚀 Deployment

### Deploy on Vercel (Recommended)

1. Push code to GitHub
2. Connect GitHub to Vercel
3. Vercel auto-deploys on push
4. Custom domain setup in Vercel dashboard

**Current Status:** ✅ Live on Vercel
```
https://portfolio-lime-sigma-56.vercel.app/
```

### Deploy Elsewhere

- **Netlify:** Connect GitHub → auto-deploy
- **GitHub Pages:** Push to gh-pages branch
- **Any static host:** Upload index.html file

---

## 🔐 SEO & Meta Tags

Optimized with:
- ✅ Semantic HTML5 structure
- ✅ Meta description
- ✅ Open Graph tags (social sharing)
- ✅ Proper heading hierarchy
- ✅ Alt text on images
- ✅ Mobile viewport tag

---

## ♿ Accessibility

- ✅ WCAG 2.1 AA compliant
- ✅ Proper color contrast (4.5:1+)
- ✅ Semantic HTML
- ✅ ARIA labels where needed
- ✅ Keyboard navigation support
- ✅ Focus indicators visible

---

## 📊 Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Latest |
| Firefox | ✅ Latest |
| Safari | ✅ Latest |
| Edge | ✅ Latest |
| Mobile Safari | ✅ iOS 12+ |
| Chrome Mobile | ✅ Latest |

---

## 🐛 Debugging

### Common Issues

**3D Globe not rendering?**
- Ensure WebGL is enabled in browser
- Check browser console for errors
- Update browser to latest version

**Animations lagging?**
- Disable hardware acceleration if needed
- Check for competing animations
- Use DevTools Performance tab

**Mobile layout broken?**
- Clear browser cache
- Check viewport meta tag
- Test on actual device

---

## 📈 Future Enhancements

- [ ] Dark/Light theme toggle
- [ ] Blog section
- [ ] Newsletter signup
- [ ] Contact form with email
- [ ] Project filtering
- [ ] Search functionality
- [ ] Analytics integration
- [ ] PWA (offline support)

---

## 🤝 Contributing

Found a bug? Want to suggest improvements?

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

## 📄 License

MIT License — see [LICENSE](LICENSE)

---

## 📞 Contact

**Built by:** Haripriya Addepalli

- 📧 Email: [haripriyaaddepalli64@gmail.com](mailto:haripriyaaddepalli64@gmail.com)
- 🔗 LinkedIn: [linkedin.com/in/haripriya-addepalli-764b75350/](https://www.linkedin.com/in/haripriya-addepalli-764b75350/)
- 🐙 GitHub: [@HaripriyaAddepalli](https://github.com/HaripriyaAddepalli)

---

## 🙏 Credits

- **Fonts:** Google Fonts (Inter, Fira Code)
- **Design Inspiration:** Modern portfolio trends
- **3D Graphics:** Canvas API + vanilla JavaScript

---

**⭐ If you like this portfolio, star it on GitHub!**

*Last updated: June 2026*
