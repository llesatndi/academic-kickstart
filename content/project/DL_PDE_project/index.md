---
title: Applying Deep Learning to PDEs
summary: Opening new fields to computational physics using deep learning.
tags:
- Deep Learning
- PDE
- ROM
- Convolutional networks
- data representation
- Neural networks
- Deep Neural Networks
date: "2019-04-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Integration of Deep Learning in the ROM framework
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
_In april 2019, I have started my first post-doc at **NTU** (Singapore) under the supervision of Pr. Li-Lian Wang. I have decided to give a new approach to my research while relying on the same ROM framework. The goal is to implement a ROM that uses the proven ability of Neural Networks, thanks to deep learning strategies, to devise a robust and accurate solvers. Several approaches will be investigated including NN-stabilization of POD-Galerkin and complete decoupling of offline/online phases._

**Motivation**:

Since the 1990s, many economic sectors including industry, finance, etc. have been relying increasingly on modelling and scientific computing (SC). Standard SC approaches such as Finite Elements are known to be robust and accurate. However, they suffer insurmountable difficulties when the number of dimensions of the problem grows beyond 3 which is typical of Black-Scholes equation (finance) e.g. d=100 or in engineering for control and optimization problems. This issue where the number of degrees of freedom (DoFs) grows beyond computers capacity (e.g. 1 billion unknowns) is called the curse of dimensionality.

Reduced Order Modelling (ROM) is a leading approach to circumvent this issue. ROM relies on the assumption that the solutions of PDEs live in space of small dimension. Numerically, this means that very few DoFs are needed to give an accurate representation of the solution and thus solve the equation. Reduced Bases (RB) have been successful at many problems but require, in most cases, a problem specific design since naive implementation like POD-Galerkin suffer instability due to non-linearities.

Machine Learning and in particular Deep Learning (DL) have gained incredible traction thanks to their ability at capturing non-linear behaviour and surpass humans at task computers were reputed unable to perform 20 years ago. Consequently, interest of the SC community has grown in the last few years with several proofs of concept.
