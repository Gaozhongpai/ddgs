# DDGS-CT — Project Page

Project page for **DDGS-CT: Direction-Disentangled Gaussian Splatting for Realistic Volume Rendering** (NeurIPS 2024,
[arXiv 2406.02518](https://arxiv.org/abs/2406.02518)).

Live at https://gaozhongpai.github.io/ddgs/ — part of the [NDSplat](https://gaozhongpai.github.io/ndsplat/) line
(DDGS, 6DGS, 7DGS, UBS, dGS/dBS, Render-FM, XClipGS, FactorSplat).

## Structure

```
index.html                 # single page
static/css/                # Bulma + shared NDSplat theme (ndsplat-theme.css)
static/js/ndsplat-nav.js   # shared nav + scroll reveal
static/images/             # figures rendered from the paper PDFs
```

Fully static. Preview with `python3 -m http.server 8000`.

Built on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
(adapted from [Nerfies](https://nerfies.github.io)), licensed CC BY-SA 4.0.
