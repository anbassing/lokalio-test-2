# LOKALIO — Vercel-ready static prototype

This package is cleaned from the Stitch export and structured as a static multi-page website.

## Deploy structure
- `/index.html` — Home
- `/explore/` — Explore Experiences
- `/destinations/` — Destination Guide
- `/experiences/jakarta-heritage-batavia/` — Experience detail
- `/business/` — Business Experiences & Strategic Services
- `/about/`, `/partner/`, `/contact/`, `/faq/`, `/inquiries/` — lightweight secondary pages
- `/legal/terms/`, `/legal/privacy/` — prototype legal placeholders
- `/assets/lokalio-logo.svg` — local brand logo

## Vercel
Import the GitHub repository as a static project. No build command is required.

If Vercel asks for a framework, choose **Other** / static site. Keep the output directory as the repository root.

## Hostinger later
The same folder structure can be uploaded to `public_html` or deployed from GitHub as a static site.

## Notes
The Stitch-generated visual system, Tailwind configuration, typography, and imagery are preserved. Navigation placeholders have been converted into real static routes, and the main LOKALIO logo is now local so it does not depend on the Stitch logo asset.
