# ggplot2 book — Community Fork

[![Build Status](https://travis-ci.org/hadley/ggplot2-book.svg?branch=master)](https://travis-ci.org/hadley/ggplot2-book)

> **Fork by [Mosiur Rahman](https://github.com/Mosiuropu)** of the original
> [hadley/ggplot2-book](https://github.com/hadley/ggplot2-book).
> Original book: [ggplot2-book.org](http://ggplot2-book.org/)

---

## What's new in this fork

### New chapter: Agricultural & Plant Breeding Data Visualization

Located in [`agricultural-breeding-viz.Rmd`](agricultural-breeding-viz.Rmd).

Practical ggplot2 patterns for **plant breeders and agricultural scientists**:

| Section | What you learn |
|---------|----------------|
| BLUP Distribution Plot | Rank genotypes by predicted breeding values |
| GxE Interaction Plot | Visualise stability across multi-environment trials |
| Multi-Trait Heatmap | Pearson correlation matrix for selection index design |
| Genomic PCA Biplot | Population structure from SNP marker data |
| Field Trial Layout | Spatial gradient detection in alpha-lattice designs |
| `theme_q1_journal()` | Publication-ready theme for Q1 plant science journals |

All examples use **self-contained simulated data** — no external files required.

### Other changes

- `index.Rmd` — fork attribution added
- `preface-fork.Rmd` — new preface section describing fork contributions
- `_bookdown.yml` — new chapter registered in build order

---

## Installing dependencies

```r
# install.packages("devtools")
devtools::install_deps()
install.packages(c("ggrepel", "scales", "dplyr", "tidyr"))
```

## Build the book

In RStudio, press Cmd/Ctrl + Shift + B. Or run:

```R
bookdown::render_book("index.Rmd")
```

---

*Original book content © Hadley Wickham. Fork additions contributed under the same Creative Commons licence.*
