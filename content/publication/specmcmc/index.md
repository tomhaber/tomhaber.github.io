---
title: "Relaxing Scalability Limits with Speculative Parallelism in Sequential Monte Carlo"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Balazs Nemeth
- admin
- Jori Liesenborgs
- Win Lamotte

date: "2018-09-01"
doi: "10.1109/CLUSTER.2018.00065"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In IEEE International Conference on Cluster Computing (CLUSTER)
publication_short: In *CLUSTER*

abstract: "  Sequential Monte Carlo methods are a useful tool to tackle non-linear problems in a Bayesian setting. A target posterior distribution is approximated by moving a set of weighted particles through a sequence of distributions. To counteract degeneracy caused by sequentially changing the underlying distribution, particles occasionally need to be resampled. Deciding if this is necessary requires a reduction operation on the weights after each update. Hence, scalability on a cluster is not only determined by the number of particles used, but also by how well load is balanced. This paper shows how speculative execution in Sequential Monte Carlo with Markov Chain Monte Carlo steps can improve parallel scalability. The key insight is that decisions taken based on the reduction result in each step can be accurately predicted. Consequently, synchronization inherent in the reduction can, in most cases, be avoided, relaxing the limit imposed by load imbalance. Particles are renumbered during resampling to further improve accuracy. Multiple test scenarios, each with different load balance characteristics, are studied empirically on a compute cluster. Tests show that when decisions are predicted correctly, execution time is reduced drastically for use cases with high load imbalance. Furthermore, the maximum theoretical gain, derived from execution characteristics, is compared with the measured improvement to verify that most speculative evaluations are actually useful. If predictions are incorrect, or load is balanced, speculation has no measurable negative impact. Performance is also evaluated in a weak scaling setting on cluster with 36 cores in each system."

tags: [Speculative Parallelism, Sequential Monte Carlo, High Performance Computing, Load Imbalance]

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
  caption: ""
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
