# Grampians Hockey Club Website

This repository contains a static Tailwind CSS build of the Grampians Hockey Club website that mirrors the live content hosted on Hugging Face Spaces. Each page is a standalone HTML file that loads Tailwind, AOS, and Feather Icons from public CDNs, so no build tooling is required.

## Pages

- `index.html` – landing page with club values, team highlights, sponsors, and newsletter signup.
- `about.html` – club history, committee profiles, and facilities overview.
- `teams.html` – interactive tabs covering juniors, women, men, and masters programmes.
- `socials.html` – social media links, upcoming events, gallery, and newsletter CTA.
- `get-involved.html` – ways to participate as a player, volunteer, or supporter.
- `contact.html` – enquiry form, contact details, and map placeholder.

## Working with the site

1. Open any of the HTML files directly in a browser to preview the page.
2. Tailwind classes are pulled from the CDN, so ensure you have an internet connection when testing locally.
3. Shared header/footer content is duplicated across pages; update each file when making global changes.

## Deployment

Because the project is fully static, hosting only requires serving the HTML files. Any static file host (e.g. GitHub Pages, Netlify, or an S3 bucket) can be used without additional configuration.
