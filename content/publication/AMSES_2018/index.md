---
markup: mmark
title: "Reduced order model of flows by time-scaling interpolation of DNS data"
authors:
- Tapan K Sengupta
- admin
- S I Haider
- Atchyut Gullapalli
- Mejdi Azaiez
date: "2018-10-01T00:00:00Z"
doi: "10.1186/s40323-018-0119-2"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Advanced Modeling and Simulation in Engineering Sciences* (AMSES)"
publication_short: ""

abstract: A new reduced order model (ROM) is proposed here for reconstructing super-critical flow past circular cylinder and lid driven cavity using time-scaling of vorticity data directly. The present approach is a significant improvement over instability-mode (developed from POD modes) based approach implemented in Sengupta et al. [Phys Rev E 91(4):043303, 2015], where governing Stuart--Landau--Eckhaus equations are solved. In the present method, we propose a novel ROM that uses relation between Strouhal number (St) and Reynolds number (Re). We provide a step by step approach for this new ROM for any Re and is a general procedure with vorticity data requiring very limited storage as well as being extremely fast. We emphasize on the scientific aspects of developing ROM by taking data from close proximity of the target Re to produce DNS-quality reconstruction, while the applied aspect is also shown. All the donor points need not be immediate neighbors and the reconstructed solution has equivalent relaxed accuracy. However, one would restrain the range where the flow behavior is coherent between donors. The reported work is a proof of concept utilizing the external and internal flow examples, and this can be extended for other flows characterized by appropriate Re--St data.},


# Summary. An optional shortened abstract.
summary:

tags:
- time-scaling
- interpolation
- LDC
- Flow past a circular cylinder
- ROM
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://amses-journal.springeropen.com/track/pdf/10.1186/s40323-018-0119-2
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
  caption: 'Ranges of unstable flow in singular lid driven cavity at Re=8800'
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
