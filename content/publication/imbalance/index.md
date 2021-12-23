---
title: "An Investigation into the Performance of Reduction Algorithms under Load Imbalance"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Petar Marendic
- Jan Lemeire
- admin
- Dean Vucinic
- Peter Schelkens

date: "2012-08-01"
doi: "10.1007/978-3-642-32820-6_44"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "European Conference on Parallel Processing"
publication_short: EuroPAR

abstract: Today, most reduction algorithms are optimized for balanced workloads; they assume all processes will start the reduction at about the same time. However, in practice this is not always the case and significant load imbalances may occur and affect the performance of said algorithms. In this paper we investigate the impact of such imbalances on the most commonly employed reduction algorithms and propose a new algorithm specifically adapted to the presented context. Firstly, we analyze the optimistic case where we have a priori knowledge of all imbalances and propose a near-optimal solution. In the general case, where we do not have any foreknowledge of the imbalances, we propose a dynamically rebalanced tree reduction algorithm. We show experimentally that this algorithm performs better than the default OpenMPI and MVAPICH2 implementations.

tags: [MPI, imbalance, collective, reduction, process skew, benchmarking]

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
---
