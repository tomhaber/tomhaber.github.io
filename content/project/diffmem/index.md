---
title: DiffMEM
summary: Scalable Differential equation based Mixed-Effects modelling
tags:
- Non-linear
- Mixed effects models
- High-Performance Computing
- Parallel

date: "2018-05-23"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
- icon: bitbucket
  icon_pack: fab
  name: Source code
  url: https://bitbucket.org/tomhaber/diffmem/
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

Existing tools (NONMEM, SAS, Winbugs) are not well suited for complex models and high-performance. The algorithms used are not always very suitable for use with large numbers of parameters and complicated non-linear models. And more importantly the hardware landscape has changed tremendously since those tools were developed: single core chip performance has begun to stagnate with a resulting move to multicore and more parallelism.

DiffMEM is tool for Non-Linear Mixed Effect model optimization in a frequentist and Bayesian context built specifically for complex models (mostly ordinary/partial differential equations) and performance. Through heavy the use of parallism, extensive low-level optimizations and algorithmic innovation, it is able to rapidly fit complex models. This in turn allows for shorter duty-cycles while building a model, and enables adaptive/optimal trial design and model validation since those typically require a lot of simulation+estimation steps.
