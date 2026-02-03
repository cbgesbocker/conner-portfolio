# Conner Gesbocker - Professional Portfolio

A clean, modern portfolio website showcasing 10+ years of web development experience and current role as a Lead Software Engineer at Capital One.

## Features

- **Responsive Design** — Mobile-first, looks great on all devices
- **Nature-Inspired Theme** — Earth tones (sage green, forest green) with subtle mountain motifs
- **Professional Layout** — About, Experience, Education, Skills, and Contact sections
- **Fast & Lightweight** — Pure HTML/CSS, no build tools needed
- **SEO-Friendly** — Semantic HTML and optimized metadata

## Tech Stack

- HTML5
- CSS3 (Grid, Flexbox, CSS Variables)
- No frameworks or dependencies

## Local Development

```bash
# Python
python -m http.server 8000

# Node
npx serve
```

Then visit `http://localhost:8000`

## File Structure

```
conner-portfolio/
├── index.html          # Main page
├── css/
│   └── style.css       # All styling
├── README.md
└── .gitignore
```

## Customization

### Colors
Edit the CSS variables in `css/style.css` (`:root` section):
```css
--color-primary: #2d5016;      /* Forest green */
--color-secondary: #6b8e23;    /* Olive green */
--color-accent: #8fbc8f;       /* Sage green */
```

### Content
Update text directly in `index.html`:
- About section
- Experience timeline
- Skills tags
- Links (LinkedIn, GitHub, Email)

### Fonts
Currently using:
- **Display:** Poppins (Google Fonts)
- **Body:** Merriweather (Google Fonts)

Change the links in `<head>` to use different fonts.

## Deployment

### GitHub Pages

1. Create a repository named `conner-portfolio`
2. Push this code to `main` branch
3. Enable GitHub Pages in repo settings
4. Set source to `main` branch

Your site will be live at: `https://cbgesbocker.github.io/conner-portfolio`

### Custom Domain

After setting up GitHub Pages:
1. Add a CNAME file with your domain
2. Update DNS records to point to GitHub Pages

## Features to Consider Adding

- Blog section for technical writing
- Project showcase gallery
- Testimonials section
- Dark mode toggle
- Newsletter signup

---

Built with care. Updated 2026.
