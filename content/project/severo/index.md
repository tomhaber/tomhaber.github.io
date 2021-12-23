---
title: Severo.jl
summary: Software package for scalable analysis and exploration of single-cell RNA-seq datasets
tags:
- single-cell
- RNA-sequencing
- High-Performance Computing
- Parallel

date: "2020-10-23"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
- icon: bitbucket
  icon_pack: fab
  name: Source code
  url: https://github.com/ExaScience/Severo.jl
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Severo.jl was created for the scalable analysis of single-cell RNA-seq datasets: the implementation is designed to minimize hardware resources such as memory while maximizing performance through parallelism and hardware optimizations.

Severo.jl gives an order of magnitude speedup when compared to other existing packages such as Seurat and Scanpy.

The package provides a toolbox of different algorithms and statistical methods from which the user can pick and choose.
