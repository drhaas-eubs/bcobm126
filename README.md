# BCOBM126 — Creativity & Design Thinking

Course portal for **BCOBM126 Creativity & Design Thinking** (Bachelor, FHEQ Level 4) at EU Business School, by **Dr. Hildegard Haas**.

A single-page static site with ten teaching units, an interactive framework gallery, an author Slibrary, and downloadable print-ready PDF reference sheets. Built to be hosted on **GitHub Pages** with no build step.

## What's inside

| Section | Content |
|---|---|
| **Course Units** | 10 active-learning units — core message, framework gallery, activity, case study, pre-reading, reflection and author Slibrary each |
| **Framework Gallery** | 39 frameworks in 10 Slibraries (one per unit); every card opens a one-page PDF sheet |
| **Slibrary — Authors** | 19 thinkers, each with a six-section profile and a downloadable PDF |
| **Course Documents** | Glossary, self-assessment and full Harvard reference list (PDF) |

All framework sheets follow a professional reference layout (definition, who/why/how/when/by-whom, innovation, related frameworks, Harvard sources). Author profiles follow a six-section layout (why, foundation, frameworks·tools·models, operationalisation, limitations, enduring impact) with pull-quotes and selected works. Referencing is Harvard (Cite Them Right) throughout.

## Structure

```
.
├── index.html                  # the portal (open this)
├── data.js                     # framework + author + slibrary data
├── .nojekyll                   # tells GitHub Pages to serve assets/ verbatim
└── assets/
    ├── frameworks/             # 39 framework PDF sheets  (fw_<slug>.pdf)
    ├── authors/                # 19 author PDF profiles   (au_<slug>.pdf)
    ├── docs/                   # glossary · self-assessment · references (PDF)
    └── thumbs/                 # SVG gallery thumbnails
        ├── frameworks/  authors/  docs/
```

## Publishing to GitHub Pages

1. Create a new repository (e.g. `bcobm126`).
2. Upload the entire contents of this folder to the repository root (keep the folder structure).
3. In **Settings → Pages**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Your site goes live at `https://<username>.github.io/<repo>/`.

The `.nojekyll` file is required so that the `assets/` directory and files are served exactly as uploaded.

## Design

- Palette: indigo `#2F3465` / amber `#B45309` with per-unit Itten accent colours; Arial throughout.
- Framework sheets and thumbnails carry per-unit accent colours; author material uses the amber accent.
- Thumbnail Thinking after **JD Meier** (2025); core-message distillation after **Kurt Bostelaar**.

## Notes

- Layouts were verified numerically; please review a few PDFs visually before printing or publishing.
- All materials © Dr. Hildegard Haas · EU Business School. All rights reserved.
