---
title: "Macau: Scalable Bayesian factorization with high-dimensional side information using MCMC"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Jaak Simm
- Adam Arany
- Pooya Zakeri
- admin
- Joerg Kurt Wegner
- Vladimir Chupakhin
- Hugo Ceulemans
- Yves Moreau

date: "2017-09-01"
doi: "10.1109/MLSP.2017.8168143"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Workshop on Machine Learning for Signal Processing"
publication_short: MLSP

abstract: Bayesian matrix factorization is a method of choice for mak-ing  predictions  for  large-scale  incomplete  matrices,  due  to availability of efficient Gibbs sampling schemes and its robustness to overfitting.  In this paper, we consider factorization of large scale matrices with high-dimensional side information. However, sampling the link matrix for the side information with standard approaches costs O(F^3) time, where F is the dimensionality of the features.  To overcome this limitation we, firstly, propose a prior for the link matrix whose strength is proportional to the scale of latent variables.  Secondly,  using  this  prior  we  derive  an  efficient  sampler,  with linear complexity in the number of non-zeros, O(Nnz), by leveraging Krylov subspace methods, such as block conjugate gradient, allowing us to handle million-dimensional side in-formation. We demonstrate the effectiveness of our proposed method in drug-protein interaction prediction task

tags: [matrix  factorization,  side  information,high scale machine learning, MCMC]

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
