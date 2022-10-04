---
title: "Reduced Order Modeling Using Advection-Aware Autoencoders"
authors:
- Sourav Dutta
- Peter Rivera-Casillas
- Brent Styles
- Matthew Farthing
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2022-04-21"
doi: "10.3390/mca27030034"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Mathematical and Computational Applications*(MCA)"
publication_short: ""

abstract: Physical systems governed by advection-dominated partial differential equations (PDEs) are found in applications ranging from engineering design to weather forecasting. They are known to pose severe challenges to both projection-based and non-intrusive reduced order modeling, especially when linear subspace approximations are used. In this work, we develop an advection-aware(AA) autoencoder network that can address some of these limitations by learning efficient, physics-informed, nonlinear embeddings of the high-fidelity system snapshots. A fully non-intrusive reduced order model is developed by mapping the high-fidelity snapshots to a latent space defined by an AA autoencoder, followed by learning the latent space dynamics using a long-short-term memory (LSTM) network. This framework is also extended to parametric problems by explicitly incorporating parameter information into both the high-fidelity snapshots and the encoded latent space. Numerical results obtained with parametric linear and nonlinear advection problems indicate that the proposed framework can reproduce the dominant flow features even for unseen parameter values.

# Summary. An optional shortened abstract.
summary: A novel autoencoder architecture is proposed to construct efficient reduced order models for advection-dominated PDEs. Numerical results are presented for parametric, linear and nonlinear advection-dominated problems.

tags:
- Deep autoencoder
- Advection-dominated flows
- Physics-informed machine learning
- LSTM
- Parametric model order reduction
- Non-intrusive reduced order modeling
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://doi.org/10.3390/mca27030034
url_code: 'https://github.com/erdc/aa_autoencoder_mca'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**MCA**](https://doi.org/10.3390/mca27030034)'
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
