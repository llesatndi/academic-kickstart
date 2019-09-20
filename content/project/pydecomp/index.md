---
title: pydecomp V1.0 software
summary: "A tensor decomposition software in python.
"
tags:
- tensor decomposition
- low rank approximation
- POD
- SVD
- HOSVD
- TT
- python
- open source
date: "2018-10-16T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

links:
- icon: github
  icon_pack: fab
  name: Repo
  url: https://git.notus-cfd.org/llestandi/python_decomposition_library

image:
  caption: Architecture of pydecomp
  focal_point: smart
---
As part of my thesis, I developed a software for computing tensor decomposition
in several formats including Canonical, Tucker, TT, Recursive format.
This library also allows continuous formulation of these decomposition.
The first version was written in **fortran** but the major programming difficulties
concerned IO with other programs and memory use, not CPU time. This is why a second
version was programmed in python. It now offers interface with several standard
data formats, efficient binary storage and readable benchmarks. </br>

The technical background (math) and a series of numerical experiments are presented
in my thesis.</br>

**Status: V1.0** The project is itself is complete as it reached its goals. However
some new features might be added in the future depending on the requirement of my
work. For instant a (very) low rank Deep Neural Network representation module is
likely in the coming months.

* **Lucas Lestandi** design the architecture and fortran version.
* **Diego Britez** (research intern) programmed most of the python version.
