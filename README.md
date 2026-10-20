<div align="center">
  <a href="https://rushikeshgarad2024-dev.github.io/dream-garden-landing/">
    <img src="assets/preview.jpg" alt="HiJOY — Dress the dream" width="100%" />
  </a>
</div>

<div align="center">

# HiJOY — Dream Garden

**A surreal botanical fashion campaign that unfolds as you scroll.**

[![Live Demo](https://img.shields.io/badge/LIVE_DEMO-Open_site-06070a?style=for-the-badge&logo=googlechrome&logoColor=8be9ff)](https://rushikeshgarad2024-dev.github.io/dream-garden-landing/)
[![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)

</div>

---

## The idea

HiJOY's dream garden is a fashion editorial that behaves like a dream: floral collages drift, chapters assemble, and the collection reveals itself only after the page has earned your attention.

The site uses a long-form scroll timeline with pinned scenes, pointer-reactive botanical layers, and a lookbook with product descriptions and a shopping-bag dialog.

## Highlights

- **Multi-scene scroll story** — opening dream, "reality recut", assembly, and collection chapters.
- **Layered botanical art** — oversized florals, eye motifs, butterflies, and sculptural fragments with depth.
- **Editorial typography** — Limelight display type paired with Italiana and Manrope.
- **Lookbook + bag** — structured look descriptions and an accessible shopping-bag dialog.
- **Responsive staging** — layouts recompose for tablet and mobile rather than simply shrinking.
- **Zero build** — one static page, ready for GitHub Pages.

## Tech

| Layer | Choice |
| :--- | :--- |
| Markup | Semantic HTML5 |
| Styling | Modern CSS, layered transforms, fluid type |
| Motion | Vanilla JS scroll timeline + pointer parallax |
| Assets | Remote editorial imagery, loaded progressively |
| Build | None |

## Run locally

```bash
# from the project root
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Structure

```text
.
├── index.html      # page, styles, scroll engine inline
└── assets/
    └── preview.jpg # README preview
```

## Credits

Build and art direction by **[Rushikesh Garad](https://github.com/rushikeshgarad2024-dev)**.
Concept adapted from the HiJOY dream-garden design by **[MahumSamar](https://github.com/MahumSamar/hijoy-dream-garden)**.
