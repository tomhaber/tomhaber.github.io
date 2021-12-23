---
title: "Fast derivatives of likelihood functionals for ODE based models using adjoint-state method"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Valdemar Melicher
- admin
- Wim Vanroose

date: "2017-12-01"
doi: "10.1007/s00180-017-0765-8"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computational Statistics"
publication_short: CompStats

abstract: We consider longitudinal data modeled by ordinary differential equations (ODEs), widespread models in physics, chemistry, biology and science in general. The sensitivity analysis of such dynamical systems usually requires calculation of various derivatives with respect to the model parameters. We employ the adjoint state method (ASM) for efficient computation of the first and the second derivatives of likelihood functionals constrained by ODEs. Essentially, the gradient can be computed with a cost (measured by model evaluations) that is independent of the number of the parameters and the Hessian with a linear cost in the number of the parameters instead of the quadratic one. The sensitivity analysis becomes feasible even if the parametric space is high-dimensional. In the theoretical part we rigorously study the ASM in the statistical context, when the discrete data are coupled with the continuous ODE model. Further, we present a highly optimized implementation of the results and its benchmarks on a number of problems.

tags: [Sensitivity Analysis, Ordinary Differential Equations, Gradient, Hessian, Statistical Computing, Mathematical Statistics, Algorithm]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- diffmem
---
