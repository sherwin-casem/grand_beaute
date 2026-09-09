# GRAND BEAUTE

Static HTML/CSS landing page for GRAND BEAUTE MEDICAL SPA, a beauty and aesthetic medical clinic concept. The page uses an elegant, calm visual style and Japanese content.

## Features

- Responsive Japanese-language homepage
- Hero section with booking and consultation calls to action
- Reasons to choose the clinic
- Campaign information
- Popular treatments with before-and-after displays
- Popular treatment ranking
- Case studies, beauty columns, reviews, and Instagram sections
- Local assets including the logo, hero image, and campaign images
- Google Fonts: Noto Sans JP, Noto Serif JP, and Petit Formal Script

## Project Structure

```text
.
├── index.html       # Homepage markup
├── style.css        # Layout, colors, and responsive styles
├── assets/          # Logo, photos, campaign images, and SVG icons
└── README.md        # Project overview and usage guide
```

## Getting Started

No build tools or package installation are required.

1. Clone or download the repository.
2. Open `index.html` in a browser.

To use a local server, run the following command from the project root:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

## Customization

- Update page copy, sections, and links in `index.html`.
- Update colors, spacing, typography, and responsive behavior in `style.css`.
- Add local images to `assets/` and reference them with relative paths from HTML or CSS.
- Navigation, booking buttons, and listing links currently use `#` placeholders. Replace them with real URLs before publishing.

## Notes

- Some before-and-after images reference external Unsplash URLs and may not load offline.
- An internet connection is required to load Google Fonts.
- Before publishing as a real medical service, review and update pricing, case-study information, advertising claims, disclaimers, and the privacy policy.
