# Portfolio Site Plan

## Purpose

Create a public, recruiter-focused portfolio for Carmine Costoya, an MBA candidate at UC Berkeley Haas with experience across strategy, product, operations, technology, design, and innovation.

## Direction

- Clean editorial design with a light theme and warm, professional typography.
- Four pages: Home, About, Work Experience, and Contact.
- Concise, evidence-based writing grounded in the supplied biography and resume.
- No public email address, phone number, photograph, LinkedIn link, analytics, or contact form.
- Static Jekyll architecture that GitHub Pages can publish directly from `main` and `/ (root)`.

## Technical Approach

- Markdown pages with YAML front matter.
- Reusable layouts and includes for the document shell, navigation, and footer.
- Plain semantic HTML and CSS with no JavaScript in the initial version.
- Empty `baseurl` and Jekyll URL filters for portable internal links and assets.
- `jekyll-seo-tag`, `jekyll-sitemap`, and an SVG favicon.

## Verification Targets

- All navigation and calls to action work from every page.
- Layout remains legible and usable at 375px and 1280px viewport widths.
- Keyboard focus is visible, landmarks are semantic, and colors meet accessible contrast targets.
- Lighthouse scores at least 90 in Performance, Accessibility, Best Practices, and SEO.
- Repository root contains the complete publish-ready site with no nested app or manual production build step.

## Approved Follow-up Improvements

1. Strengthen the professional story and add resume-backed impact highlights.
2. Improve navigation, responsive hierarchy, and accessibility details.

