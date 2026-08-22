# Eldred Photography

![HTML](https://img.shields.io/badge/HTML-Static%20Page-orange)

## Table of Contents
- [About](#about)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Authors and License](#authors-and-license)

## About

A single-page photography portfolio site for a photographer named "Eldred" (`index.html`). It has a full-screen hero, a filterable gallery (All / Landscape / Portrait / Urban) with a click-to-open lightbox, an About section, and a contact form. The page is entirely self-contained HTML/CSS/JS, styled with the Tailwind CDN and Font Awesome icon CDN, with fade-in-on-scroll animations via `IntersectionObserver`. The gallery images are placeholder stock photos pulled live from Unsplash (with a `via.placeholder.com` fallback via `onerror`) and given generic titles ("Mirror Lake", "City Echoes", "Human Gaze", etc.) — no real client photography or original assets are included in the repository. The contact form and mobile menu button are cosmetic only: submitting the form just shows a client-side "Message sent successfully!" toast without actually sending anything anywhere, and the mobile menu button shows a toast saying the feature "would go here" instead of opening a real menu. This is a portfolio template/demo rather than a finished, content-complete client site.

## Prerequisites

None beyond a modern browser with internet access, since Tailwind CSS, Font Awesome, and all gallery/about images are loaded from external CDNs at view time.

## Installation

```bash
git clone https://github.com/successjoseph/Eldred-Photography.git
cd Eldred-Photography
```

No dependencies or build tools are required.

## Configuration

There is no external configuration. All copy, image URLs, and gallery categories are hardcoded in `index.html`.

## Usage

Open `index.html` directly in a browser, or serve it locally:
```bash
python -m http.server 8000
```
Use the filter buttons to switch gallery categories, click any gallery image to open the lightbox (Escape or the × closes it), and use the contact form to see the (non-functional) confirmation toast.

## Testing

No automated tests are currently included.

## Contributing

This is a personal/template project rather than one open to outside contributions. Notes above are for future-you when revisiting or finishing the design.

## Authors and License

- **Author:** successjoseph ([github.com/successjoseph](https://github.com/successjoseph))
- **License:** No license file included in this repository — all rights reserved by default.
