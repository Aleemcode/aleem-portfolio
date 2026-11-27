# Aleem Akinyoola — portfolio

Static, single-page portfolio for [aleemakinyoola.com](https://aleemakinyoola.com), deployed on Vercel.

- `index.html` — the whole site (Home, Work, Brands, CV, Contact, plus project views)
- `brand-marks.html` — the Brands tab's logo marks, fetched by `index.html` when needed so the first load stays light
- `work/` — images used inside case studies (the cudie.ng captures)
- `og.jpg` — social preview image for link cards
- `cv.pdf` — downloadable CV
- `vercel.json` — clean URLs, no trailing slash

No build step. On Vercel: framework preset "Other", no build command, no output directory.
