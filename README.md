## patrick-lefler.github.io

> Personal website and analytical portfolio for a financial technology executive, built with Quarto and deployed via GitHub Pages.

**Author:** Patrick Lefler

**Published:** 2025

**Rendered:** https://patrick-lefler.github.io/

---

## Introduction

A Quarto-powered personal site presenting practitioner-level work at the intersection of financial risk, quantitative modeling, and technology strategy. The site surfaces published insights and analytical projects for boards, senior executives, and risk practitioners.

## Overview

The site is a single-page Quarto document (`index.qmd`) that aggregates dynamic listing grids for insights and projects, rendered to self-contained HTML and deployed via GitHub Pages. Brand consistency is enforced through `_brand.yml` and a custom SCSS stylesheet. Content spans fixed-income risk, volatility modeling, model governance, and cybersecurity strategy — each piece oriented toward translating quantitative output into decisions a non-technical executive can act on.

## Tech Stack

- **Language:** R
- **Framework:** [Quarto](https://quarto.org/)
- **Primary Libraries:** Tidyverse, ggplot2, plotly, kableExtra
- **Deployment / Output:** GitHub Pages (HTML)

## Repository Structure

```
├── docs/               # Rendered HTML output served by GitHub Pages
├── images/             # Profile and asset images
├── _brand.yml          # Brand configuration (colors, typography)
├── _quarto.yml         # Project-level Quarto configuration
├── _publish.yml        # GitHub Pages publish target
├── index.qmd           # Main site entry point
├── styles.scss         # Custom SCSS overrides
└── resume.pdf          # Downloadable résumé
```

## Key Findings

- Risk is most useful when treated as a quantitative, dynamic variable — not a compliance artifact. The site's projects reflect that premise across volatility forecasting, model auditing, and tail-risk estimation.
- Standard models systematically underweight low-probability, high-severity events. The analytical work here applies stochastic and statistical methods specifically to surface those gaps.
- Governance and technical execution are not separate tracks. Each project is designed to produce output a board member can read and a quant can verify.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

Patrick Lefler — [LinkedIn](https://www.linkedin.com/in/patricklefler/) | [patrick-lefler.github.io](https://patrick-lefler.github.io) | [Substack](https://substack.com/@pflefler)
