---
title: "A computational approach to simulate light diffusion in arbitrarily shaped objects"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Tom Mertens
- Philippe Bekaert
- Frank van Reeth

date: "2005-01-01"
doi: "10.1145/1089508.1089522"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the Graphics Interface"
publication_short: GI

abstract: To faithfully display objects consisting of translucent materials such as milk, fruit, wax and marble, one needs to take into account subsurface scattering of light. Accurate renderings require expensive simulation of light transport. Alternatively, the widely-used fast dipole approximation cannot deal with internal visibility issues, and has limited applicability (only homogeneous materials).We present a novel algorithm to plausibly reproduce subsurface scattering based on the diffusion approximation. This yields a relatively simple partial differential equation, which we propose to solve numerically using the multigrid method. The main difficulty in this approach consists of accurately representing interactions near the object s surface, for which we employ the embedded boundary discretization. Also, our method allows us to refine the simulation hierarchically where needed in order to optimize performance and memory usage. The resulting approach is capable of rapidly and accurately computing subsurface scattering in polygonal meshes for both homogeneous and heterogeneous materials. The amount of time spent computing subsurface scattering in a complex object is generally a few minutes.

tags: [Rendering, subsurface scattering, heterogeneous materials, embedded boundary, multigrid]

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
projects: []
---
