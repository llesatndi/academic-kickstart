---
markup: mmark
title: "Low rank approximation techniques and reduced order modeling applied to some fluid dynamics problems"
authors:
- admin
date: "2018-10-01T00:00:00Z"
doi: "10.1016/j.compfluid.2018.01.038"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "*Université de Bordeaux*"
publication_short: ""

abstract: "In the last decades, numerical simulation has experienced tremendous improvements driven by massive growth of computing power. Exascale computing has been achieved this year and will allow solving ever more complex problems. But such large systems produce colossal amounts of data which leads to its own difficulties. Moreover, many engineering problems such as multiphysics or optimisation and control, require far more power that any computer architecture could achieve within the current scientific computing paradigm. In this thesis, we propose to shift the paradigm in order to break the curse of dimensionality by introducing decomposition and building reduced order models (ROM) for complex fluid flows.</br>

This manuscript is organized into two parts. The first one proposes an extended review of data reduction techniques and intends to bridge between applied mathematics community and the computational mechanics one. Thus, founding bivariate separation is studied, including discussions on the equivalence of proper orthogonal decomposition (POD, continuous framework) and singular value decomposition (SVD, discrete matrices). Then a wide review of tensor formats and their approximation is proposed. Such work has already been provided in the literature but either on separate papers or into a purely applied mathematics framework. Here, we offer to the data enthusiast scientist a comparison of Canonical, Tucker, Hierarchical and Tensor train formats including their approximation algorithms. Their relative benefits are studied both theoretically and numerically thanks to the python library `pydecomp` that was developed during this thesis. A careful analysis of the link between continuous and discrete methods is performed. Finally, we conclude that for most applications ST-HOSVD is best when the number of dimensions $d$ lower than four and TT-SVD (or their POD equivalent) when $d$ grows larger.</br>

The second part is centered on a complex fluid dynamics flow, in particular the singular lid driven cavity at high Reynolds number. This flow exhibits a series of Hopf bifurcation which are known to be hard to capture accurately which is why a detailed analysis was performed both with classical tools and POD. Once this flow has been characterized, *time-scaling*, a new *``physics based''* interpolation ROM is presented on internal and external flows. This methods gives encouraging results while excluding recent advanced developments in the area such as EIM or Grassmann manifold interpolation."

# Summary. An optional shortened abstract.
summary:

tags:
- Data reduction
- Model Reduction
- MOR
- POD
- Lid Driven Cavity
- Low rank approximation
- Tensors
- HOSVD
- Tensor train
- Tensor formats
- Tensor approximation
- physics interpolation
- time-scaling
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://tel.archives-ouvertes.fr/tel-01947210/
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
  caption: 'ROM building workflow'
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
slides: ""
---
