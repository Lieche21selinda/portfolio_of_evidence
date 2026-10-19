# Masego Mokgoko — Portfolio of Evidence 2026

A static website (plain HTML/CSS, no build step).

## Structure
```
index.html                         ← main site: profile + link tree
├── research-outputs.html          ← PER, De Jure, CILSA, African Renaissance, NWU-RO-2025-4039
├── conferences.html               ← Aston University, UK (Aug 2026)
├── writing-retreats.html          ← Parys, Kerlick, Villa Paradiso
├── research-training.html         ← RCD Series, ethics, supervision workshop
├── phd-development.html           ← PhD proposal, McGill ASLI course
└── occupational-health-safety.html
assets/  style.css · lightbox.js · img/ (evidence photos) · docs/ (PDFs)
```

## Publish on GitHub Pages
1. Create a new repository on GitHub (e.g. `masego-portfolio`).
2. Upload **the contents of this folder** (index.html must be at the top level of the repo).
3. Go to **Settings → Pages**, under "Build and deployment" choose **Deploy from a branch**,
   branch `main`, folder `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/masego-portfolio/`.

## Editing
Open any `.html` file in a text editor to change text. To add evidence, put the image in
`assets/img/` and copy an existing `<button class="thumb" …>` block on the relevant page.
