---
title: "Improving ODE Integration on Graphics Processing Units by Reducing Thread Divergence"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Thomas Kovac
- admin
- Frank van Reeth
- Niel Hens

date: "2019-06-01"
doi: "10.1007/978-3-030-22744-9_35"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Computational Science
publication_short: ICCS

abstract: Ordinary differential equations are widely used for the mathematical modeling of complex systems in biology and statistics. Since the analysis of such models needs to be performed using numerical integration, many applications can be gravely limited by the computational cost. This paper present a general-purpose integrator that runs massively parallel on graphics processing units. By minimizing thread divergence and bundling similar tasks using linear regression, execution time can be reduced by 40–80% when compared to a naive GPU implementation. Compared to a 36-core CPU implementation, a 150 fold runtime improvement is measured.

tags: [Pharmacometrics, Epidemiology, Parallelism, High-Performance Computing, Graphics Processing Units]

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
