---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "NAP: Noise-Based Sensitivity Analysis for Programs"
authors: ["Jesse Michel", "Sahil Verma", "Benjamin Sherman", "Michael Carbin"]
date: 2019-06-22
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-27T13:37:42+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Workshop on Approximate Computing (WAX), 2019"
publication_short: ""

abstract: "Low-precision approximation of programs enables faster computation in fields such as machine learning, data analytics, and vision. Such approximations automatically transform a program into one that approximates the original output but executes much faster. At the heart of this approximation is sensitivity analysis - understanding the program's robustness to various perturbations. Sensitivity analysis provides a metric to measure how much each value in the program to produce a faster, yet accurate, approximate program.
We propose NAP (Noise-based Analyzer of Programs) which provides a novel sensitivity analysis of each operator and variable in a program. NAP performs sensitivity analysis by introducing independent Gaussian noise to each value in a program (e.g., arithmetic operator and variable reference), producing a stochastic semantics of the program."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Other"]
categories: ["Other"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: http://approximate.computer/wax2019/papers/michel.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides: WAX_Slides.pdf
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
