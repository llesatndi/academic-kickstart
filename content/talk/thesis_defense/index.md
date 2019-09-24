---
title: Low rank approximation and reduced order modeling applied to some fluid dynamics problems
event: Thesis defense
event_url: ""

location: ENSCBP Bordeaux
address:
  street: ""
  city: Bordeaux
  region: ""
  postcode: ""
  country: France

summary: "My thesis defense slides. Jury: Rozza, Cueto, Mieussens, Chacon, Azaiez, Beringhier, Rubino, Sengupta."
abstract: "In the last decades, numerical simulation has experienced tremendous improvements driven by massive growth of computing power. Exascale computing has been achieved this year and will allow solving ever more complex problems. But such large systems produce colossal amounts of data which leads to its own difficulties. Moreover, many engineering problems such as multiphysics or optimisation and control, require far more power that any computer architecture could achieve within the current scientific computing paradigm. In this thesis, we propose to shift the paradigm in order to break the curse of dimensionality by introducing decomposition and building reduced order models (ROM) for complex fluid flows.</br>

This manuscript is organized into two parts. The first one proposes an extended review of data reduction techniques and intends to bridge between applied mathematics community and the computational mechanics one. Thus, founding bivariate separation is studied, including discussions on the equivalence of proper orthogonal decomposition (POD, continuous framework) and singular value decomposition (SVD, discrete matrices). Then a wide review of tensor formats and their approximation is proposed. Such work has already been provided in the literature but either on separate papers or into a purely applied mathematics framework. Here, we offer to the data enthusiast scientist a comparison of Canonical, Tucker, Hierarchical and Tensor train formats including their approximation algorithms. Their relative benefits are studied both theoretically and numerically thanks to the python library `pydecomp` that was developed during this thesis. A careful analysis of the link between continuous and discrete methods is performed. Finally, we conclude that for most applications ST-HOSVD is best when the number of dimensions $d$ lower than four and TT-SVD (or their POD equivalent) when $d$ grows larger.</br>

The second part is centered on a complex fluid dynamics flow, in particular the singular lid driven cavity at high Reynolds number. This flow exhibits a series of Hopf bifurcation which are known to be hard to capture accurately which is why a detailed analysis was performed both with classical tools and POD. Once this flow has been characterized, *time-scaling*, a new *``physics based''* interpolation ROM is presented on internal and external flows. This methods gives encouraging results while excluding recent advanced developments in the area such as EIM or Grassmann manifold interpolation."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2018-10-16T09:30:00Z"
#date_end: "2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: ""

authors: [admin]
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
#[Tensor decomposition, POD, SVD, HOSVD]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: "files/soutenance.pdf"
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Enable math on this page?
math: true
---
