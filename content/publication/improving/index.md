---
title: "Improving the runtime performance of non-linear mixed-effects model estimation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Frank van Reeth

date: "2020-05-01"
doi: "10.1007/978-3-030-48340-1_43"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "European Conference on Parallel Processing"
publication_short: EuroPAR

abstract: Non-linear mixed effects models (NLMEM) are frequently used in drug development for pharmacokinetic (PK) and pharmacokinetic-pharmacodynamic (PK-PD) analyses. Parameter estimation for these models can be time-consuming due to the need for numerical integration. Additionally, the structural model is often expressed using differential equations requiring computationally intensive time-stepping ODE solvers. Overall, this often leads to long computation times in the order of hours or even days. Combining the right mathematical tools as well as techniques from computer science, the computational cost can be significantly reduced. In this paper, several approaches are detailed for improving the performance of parameter estimation for NLMEM. Applying these, often easy, techniques can lead to an order of magnitude speedup.

tags: [Non-linear, Mixed effects models, High-Performance Computing, Parallel]

# Display this page in the Featured widget?
featured: true

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
