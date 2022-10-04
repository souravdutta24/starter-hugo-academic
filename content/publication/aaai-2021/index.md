---
title: 'Neural Ordinary Differential Equations for Data-Driven Reduced Order Modeling of Environmental Hydrodynamics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sourav Dutta
  - Peter Rivera-Casillas
  - Matthew Farthing
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-04-22'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the AAAI 2021 Spring Symposium on Combining Artificial Intelligence and Machine Learning with Physical Sciences*
publication_short: In *AAAI MLPS 2021*

abstract: Model reduction for fluid flow simulation continues to be of great interest across a number of scientific and engineering fields. Here, we explore the use of Neural Ordinary Differential Equations, a recently introduced family of continuous-depth, differentiable networks (Chen et al. 2018), as a way to propagate latent-space dynamics in reduced order models. We compare their behavior with two classical non-intrusive methods based on proper orthogonal decomposition and radial basis function interpolation as well as dynamic mode decomposition. The test problems we consider include incompressible flow around a cylinder as well as real-world applications of shallow water hydrodynamics in riverine and estuarine systems. Our findings indicate that Neural ODEs provide an elegant framework for stable and accurate evolution of latent-space dynamics with a promising potential of extrapolatory predictions. However, in order to facilitate their widespread adoption for large-scale systems, significant effort needs to be directed at accelerating their training times. This will enable amore comprehensive exploration of the hyperparameter space for building generalizable Neural ODE approximations over a wide range of system dynamics.

# Summary. An optional shortened abstract.
summary: Reduced order modeling of time dependent PDEs using proper orthogonal decomposition and neural ordinary differental equations.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2104.13962'
url_code: 'https://github.com/erdc/node_nirom'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/U9F2zL-_Vk8m'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: ''
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
