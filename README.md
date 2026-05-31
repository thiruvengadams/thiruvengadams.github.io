# Thiruvengadam S — personal site

Source for **[thiruvengadams.github.io](https://thiruvengadams.github.io/)** — the personal site of
Thiruvengadam S, Staff AI Researcher at Hitachi's R&D Center, Bengaluru.

Built as a single, fast, dependency-free static page (no build step) for GitHub Pages. Work spans
**Industrial Generative AI** (Vision-LLMs, multi-agent RAG), **NLP & speech** for inclusive fintech,
and **time-series intelligence** for mobility.

- 🔗 Google Scholar: <https://scholar.google.com/citations?user=hG3zpVkAAAAJ&hl=en>
- 💼 LinkedIn: <https://www.linkedin.com/in/thiruvengadamsamon>
- 📄 CV: [`assets/Thiruvengadam_S_CV.pdf`](assets/Thiruvengadam_S_CV.pdf)

## Structure

```
index.html      # the whole site (HTML + CSS + minimal JS, light/dark, SEO + JSON-LD)
robots.txt      # crawler rules + sitemap reference
sitemap.xml     # single-page sitemap
assets/
  profile.jpg   # profile photo (web-optimized)
  og-card.png   # 1200×630 social-share card
  favicon.svg   # "TS" monogram favicon
  Thiruvengadam_S_CV.pdf
```

## How to update

- **Photo** — replace `assets/profile.jpg` (square-ish JPEG, ≤ ~250 KB; portrait works, it's
  center-cropped to a circle). Re-export the share card if you want it refreshed.
- **CV** — replace `assets/Thiruvengadam_S_CV.pdf`.
- **Publications / patents** — edit the `#publications` and `#patents` sections in `index.html`,
  and mirror entries in the JSON-LD `ItemList` in `<head>` so search engines stay in sync.
- **Optional hero background** — drop an image at `assets/hero-bg.jpg`; the hero will pick it up
  automatically as a faint backdrop.

## Deploy

GitHub Pages serves the `main` branch automatically. Push to `main` and the site rebuilds in ~1–2 min.
