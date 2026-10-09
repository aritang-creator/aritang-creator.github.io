# Chloe Chan — Personal Website

A personal portfolio website for Chloe Chan, MSc Marketing Candidate at HKU Business School.

## Preview

![Chloe Chan Website](chloe-photo.png)

Live site: `https://YOUR-USERNAME.github.io/chloe-chan-website/`

## About

An editorial magazine-style personal website showcasing:

- Professional experience (L'Oréal HK, HSBC HK, Ogilvy HK, Harbour & Pine Coffee)
- Academic background (HKU MSc Marketing, HKUST BBA Management)
- Selected projects (Sustainable Fashion Study, "Hidden Hong Kong", Gen Z Beauty Trends Dashboard)
- Skills and certifications (GA4, Tableau, SPSS, Figma, Google Analytics, Meta, HubSpot)
- Leadership and community involvement
- Languages and contact information

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Structure | Single-page HTML |
| Styling | Embedded CSS (no external stylesheets) |
| Interactivity | Vanilla JavaScript (mobile menu) |
| Fonts | Google Fonts — Playfair Display & Inter |
| Images | 1 headshot photo (`chloe-photo.png`) |

No build tools, no frameworks, no dependencies. Just open `index.html` in a browser.

## File Structure

```
chloe-chan-website/
├── index.html        # The entire website (HTML + CSS + JS)
├── chloe-photo.png   # Headshot photo (displayed in hero section)
└── README.md         # This file
```

## Design

- **Template:** Editorial Magazine (Template B)
- **Accent color:** Coral (`#993C1D`)
- **Background:** Warm off-white (`#FDFBF7`)
- **Headlines:** Playfair Display (serif)
- **Body text:** Inter (sans-serif)
- **Layout:** Two-column editorial flow with a left main column and right sidebar
- **Responsive:** Mobile-friendly with hamburger navigation menu

## Local Development

To preview locally, simply open `index.html` in any web browser:

```bash
# macOS
open index.html

# Or start a simple local server
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Deployment (GitHub Pages)

1. Create a new **public** repository on GitHub
2. Upload both `index.html` and `chloe-photo.png` to the repository root
3. Go to **Settings → Pages**
4. Set **Source** to "Deploy from a branch"
5. Select **main** branch and **/ (root)** folder
6. Click **Save**
7. Your site will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/` within 30–60 seconds

## Customization

| What to change | Where in `index.html` |
|----------------|-----------------------|
| Name / title | `<title>` tag and `.nav-logo` |
| Headline | `.hero-title` |
| Contact info | `.hero-meta` and `footer` links |
| Work experience | `.work-card` elements |
| Projects | `.project-card` elements |
| Skills | `.skill-tag` spans |
| Accent color | `--coral` CSS variable in `:root` |
| Photo | Replace `chloe-photo.png` |

## License

Personal website for Chloe Chan. All content is based on an academic CV and should not be reused without permission.

---

Built from CV with editorial design.
