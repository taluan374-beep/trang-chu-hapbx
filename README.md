# HaPBX Homepage

A modern, engineer-centric homepage for HaPBX - Enterprise-Grade VoIP Infrastructure.

## Holiday Notice Poster (Octopool) — 2026

This repo also includes a standalone, print-friendly holiday notice poster (VN + EN):

- File: `holiday-notice-2026.html`
- Content (Vietnamese): **Thông báo nghỉ Tết Dương lịch 2026** (đóng cửa 01/01–02/01/2026, mở cửa lại 03/01/2026)
- Notes: Vietnamese spelling and wording have been standardized (e.g. “wealth”, “thịnh vượng”, “Tết Dương lịch”).

### Open / Export

- Open directly in a browser (double-click the file), then use **Print → Save as PDF** to export.

## Overview

This homepage is designed specifically for technical audiences (DevOps, VoIP Engineers, IT Managers) who value:
- Technical accuracy and clarity
- Clean, minimalist design with high contrast
- Real feature demonstrations over marketing fluff

## Design Philosophy

### Visual Style
- **Color Palette**: Yellow (#FACC15) / Black (#0A0A0A) / White
- **Typography**: Inter (headings) + JetBrains Mono (code/technical)
- **Approach**: Engineer-centric with focus on technical specs and real UI previews

### UX Principles
- Reduce friction - show don't tell
- Technical demonstrations (code snippets, architecture diagrams)
- No generic stock photos

## Page Sections

| Section | Purpose |
|---------|---------|
| Hero | Split-screen with value prop + interactive terminal preview |
| Tech Stack Logos | Trust through integration partners |
| Architecture Breakdown | Visual explanation of high availability |
| Feature Deep Dive | Interactive tabs showing actual UI previews |
| Pricing | Transparent comparison table with technical specs |
| Developer Resources | Dark-mode cards for API, Status, Knowledge Base |
| Footer | Clean navigation with organized links |

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Via CDN with custom configuration
- **Vanilla JavaScript** - For tab switching and mobile menu

## Quick Start

Simply open `index.html` in a browser. No build process required.

```bash
# Open in default browser (macOS)
open index.html

# Or serve locally
python -m http.server 8000
```

## Customization

### Brand Colors
Edit the Tailwind config in `<script>` tag:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                brand: {
                    yellow: '#FACC15',
                    'yellow-hover': '#EAB308',
                    black: '#0A0A0A',
                    // ...
                }
            }
        }
    }
}
```

### Content
All content is inline HTML - edit sections directly in `index.html`.

## Features

- ✅ Fully responsive (mobile-first)
- ✅ Interactive tab navigation
- ✅ Mobile menu toggle
- ✅ Smooth scroll navigation
- ✅ Animated elements (pulse, hover states)
- ✅ Accessible markup
- ✅ No external dependencies (CDN only)

## Browser Support

Modern browsers (Chrome, Firefox, Safari, Edge) with ES6+ support.

## License

MIT
