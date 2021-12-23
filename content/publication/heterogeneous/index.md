---
title: "Heterogeneous computing for epidemiological model fitting and simulation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Thomas Kovac
- admin
- Frank van Reeth
- Niel Hens

date: "2018-03-01"
doi: "10.1186/s12859-018-2108-3"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "BMC Bioinformatics"
publication_short: BMC

abstract: "
## Background

Over the last years, substantial effort has been put into enhancing our arsenal in fighting epidemics from both technological and theoretical perspectives with scientists from different fields teaming up for rapid assessment of potentially urgent situations. This paper focusses on the computational aspects of infectious disease models and applies commonly available graphics processing units (GPUs) for the simulation of these models. However, fully utilizing the resources of both CPUs and GPUs requires a carefully balanced heterogeneous approach.

## Results

The contribution of this paper is twofold. First, an efficient GPU implementation for evaluating a small-scale ODE model; here, the basic S(usceptible)-I(nfected)-R(ecovered) model, is discussed. Second, an asynchronous particle swarm optimization (PSO) implementation is proposed where batches of particles are sent asynchronously from the host (CPU) to the GPU for evaluation. The ultimate goal is to infer model parameters that enable the model to correctly describe observed data. The particles of the PSO algorithm are candidate parameters of the model; finding the right one is a matter of optimizing the likelihood function which quantifies how well the model describes the observed data. By employing a heterogeneous approach, in which both CPU and GPU are kept busy with useful work, speedups of 10 to 12 can be achieved on a moderate machine with a high-end consumer GPU as compared to a high-end system with 32 CPU cores.

## Conclusions

Utilizing GPUs for parameter inference can bring considerate increases in performance using average host systems with high-end consumer GPUs. Future studies should evaluate the benefit of using newer CPU and GPU architecture as well as applying this method to more complex epidemiological scenarios.
"

tags: [ODE,PDE,Infectious diseases, Epidemiology, SIR model, GPU Asynchronous, Parallel, Particle Swarm Optimization, Heterogeneous computing]

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
