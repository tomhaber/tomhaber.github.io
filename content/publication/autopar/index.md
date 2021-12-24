---
title: "Automatic Parallelization of Probabilistic Models with Varying Load Imbalance"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Balazs Nemeth
- admin
- Jori Liesenborgs
- Win Lamotte

date: "2020-05-01"
doi: "10.1109/CCGrid49817.2020.00-14"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In 2020 20th IEEE/ACM International Symposium on Cluster, Cloud and Internet Computing (CCGRID)
publication_short: In *CCGRID*

abstract: As scientists are designing increasingly complex and intricate models, the prominent way today to achieve acceptable execution time without sacrificing accuracy is through parallel computing. These techniques can improve execution time either on the level of the optimization methods or on the level of the model evaluations. This paper outlines an automatic parallelization approach for the latter. Processor specific procedures with embedded communication primitives are generated from static schedules produced by an evolutionary algorithm. These are passed to an optimizing compiler to avoid the overhead of typical task runtime systems. The two key insights are that the parallel structure of probabilistic models is revealed when the data is combined with the model and that static schedules can be combined into more robust schedules that can deal with varying load imbalance. For this, LogP model parameters and execution time of each computational task are measured and fed into a discrete event simulator to estimate the running time on the target parallel system. Performance is evaluated with three pharmacological models with different characteristics. The first model lacks enough exploitable parallelism while up to approximately 6x and 8x improvements are achieved for the other models. Compared to a theoretical system with infinite processors and no communication delay, this equates to exploiting 66% and 99% of the available parallelism. Performance improves even when load imbalance varies.

tags: [High Performance Computing, Descriptive Language, Probabilistic Modeling, Automatic Parallelization, Dataflow, LogP model, Simulation, Evolutionary Algorithms, Scheduling, Load Imbalance]

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
- hpc
---
