---
title: "From Conditional Independence to Parallel Execution in Hierarchical Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Balazs Nemeth
- admin
- Jori Liesenborgs
- Win Lamotte

date: "2020-06-01"
doi: "10.1007/978-3-030-50371-0_12"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Computational Science
publication_short: ICCS

abstract: Hierarchical models describe phenomena by grouping data into multiple levels. Due to the size of these models, parallel execution is required to avoid prohibitively long computing time. While it is occasionally possible to specify some of these models using parallel building blocks, this limits expressivity. Therefore, a more general generative specification is preferred. To leverage parallel computing capacity, these specifications can be annotated, but doing so effectively assumes that the modeler has expertise from computer science. This paper outlines how to identify parallel parts automatically by leveraging the conditional independence property in the graphical model extracted from the dataflow graph of model specifications. Computation related to random variables with the same depth in the graphical model are identified as candidates for parallel execution. Since subsequent proposals in the parameter space exploration of the model are clustered together, the results show that the well known longest processing time scheduling heuristic deals adequately with load imbalance. The proposed parallelization is evaluated on two pharmacometrics models, a domain where hierarchical models with load imbalance are common due to the numeric simulation of pharmacokinetics and pharmacodynamics of human subjects. The varying number of measurements taken per subject further exacerbates load imbalance.

tags: [High Performance Computing, Descriptive Language, Probabilistic Modelling, Automatic Parallelization, Dataflow, Hierarchical Models]

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
