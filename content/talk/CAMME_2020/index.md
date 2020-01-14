---
title: Advances in Deep learning aided Reduced Order Modelling for Fluid Dynamics
event: 2020 4th International Conference on Aerospace, Mechanical and Mechatronic Engineering
event_url: http://www.camme.org/

location: Nagoya
address:
  street: ""
  city: Nagoya
  region: ""
  postcode: ""
  country: Japan

summary: ""
abstract: "
Since the 1990s, almost all industries (e.g. automotive, aerospace, etc.) have been relying increasingly on modeling and numerical simulation. Standard scientific computing approaches such as Finite Elements are known to be robust and accurate. However, they suffer insurmountable difficulties when the number of dimensions of the problem grows beyond 3, typically for control and optimization problems or real-time applications. Reduced Order Modeling (ROM) is a leading approach to circumvent this issue. It relies on the assumption that the solutions of partial differential equations live in space of small dimension. Numerically, this means that very few degrees of freedom are needed to give an accurate representation of the solution and thus solve the equation. Reduced Bases (RB) have been successful at many problems but require, in most cases, a problem specific design since naive implementation like POD-Galerkin suffer instability due to non-linearities. It this talk, we explore how machine learning and in particular deep learning (DL) can help solve these issues, in particular for hyperbolic equations such as Navier-Stokes. Indeed, DL have gained incredible traction thanks to its ability at capturing non-linear behavior and surpass humans at task computers were reputed unable to perform 20 years ago.  Since 2015, it has been applied successfully to scientific computing, in particular thanks to its proven ability to represent non-linear behavior and low rank representation ability. The three dominant families of  DL techniques  (multilayer perceptron,  constitutional nets, recurrent nets) will be presented together with their most successful application to PDE reduced order models.
"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-03-23T13:00:00Z"
date_end: "2020-03-25T13:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: ""

authors: [admin]
tags: [Deep learning, ROM, NN, POD-NN, PDE]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
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
