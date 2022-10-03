---
title: "A greedy non-intrusive reduced order model for shallow water equations"
authors:
- Sourav Dutta
- Matthew Farthing
- Emma Perracchione
- Gaurav Savant
- Mario Putti
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-08-15"
doi: "10.1016/j.jcp.2021.110378"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Computational Physics*(JCP)"
publication_short: ""

abstract: In this work, we develop Non-Intrusive Reduced Order Models (NIROMs) that combine Proper Orthogonal Decomposition (POD) with a Radial Basis Function (RBF) interpolation method to construct efficient reduced order models for time-dependent problems arising in large scale environmental flow applications. The performance of the POD-RBF NIROM is compared with a traditional nonlinear POD (NPOD) model by evaluating the accuracy, robustness, and speed for test problems representative of riverine flows. Different greedy algorithms are studied in order to determine a near-optimal distribution of interpolation points for the RBF approximation. A new power-scaled residual greedy (psr-greedy) algorithm is proposed that overcomes the drawbacks of the existing greedy approaches to enhance the accuracy and efficiency of the RBF approximation. The relative performance of these greedy algorithms is studied with numerical experiments using realistic 2D shallow water flow applications involving coastal and riverine dynamics.

# Summary. An optional shortened abstract.
summary: A novel reduced order model for time-dependent PDEs using proper orthogonal decomposition and radial basis function interpolation. A new greedy algorithm for optimal selection of interpolation points is also proposed. Real world examples are presented using 2D shallow water equations.

tags:
- Greedy algorithms
- Non-intrusive reduced order model
- Proper orthogonal decomposition
- Radial basis function interpolation
- Shallow water equations
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2002.11329
url_code: 'https://github.com/erdc/podrbf_nirom'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**JCP**](https://www.sciencedirect.com/science/article/pii/S0021999121002734?via%3Dihub)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
