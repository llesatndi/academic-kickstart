---
markup: mmark
title: "Numerical Study of Low Rank Approximation Methods for Multidimensional Physics and its Analysis"
authors:
- admin

date: "2020-01-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to *Journal of scientific computing*"
publication_short: ""

abstract: This paper proposes a comparison of the numerical aspect and efficiency of several low rank approximation techniques for multidimensional data, namely CPD, HOSVD, TT-SVD and RPOD. This approach is different from the numerous papers that compare the theoretical aspects of these methods or propose efficient implementation of a single technique. Here, after a brief presentation of the studied methods, they are tested in practical conditions in order to draw hindsight at which one should be preferred. Synthetic data provides sufficient evidence for dismissing CPD, T-HOSVD and RPOD. Then, three examples from mechanics provide data for realistic application of TT-SVD and ST-HOSVD. The obtained low rank approximation provide different levels of compression and accuracy depending on how separable the data is. In all cases, the data layout has significant influence on the analysis of modes and computing time while remaining similarly efficient at compressing information. Both methods provide satisfactory compression, from 0.1% to 20% of the original size within a few percent error in L 2 norm. ST-HOSVD provides an orthonormal basis while TT-SVD doesn’t. However it is better suited for higher order d.Finally, these numerical tests have been performed with pydecomp , an open source python library developed by the author.},


# Summary. An optional shortened abstract.
summary:

tags:
- HOSVD
- ST-HOSVD
- Tensor Train
- Canonical Decomposition
- RPOD
- POD
- SVD
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'files/low_rank_approx_paper_SUBMITTED.pdf'
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
  caption: 'Schematic view of pydecomp, the software used to perform all the
  numerical experiments of this paper.'
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
