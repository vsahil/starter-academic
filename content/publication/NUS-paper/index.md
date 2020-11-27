---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Benchmarking Symbolic Execution Using Constraint Problems - Initial Results"
authors: []
date: 2019-11-04
doi: "10.1109/ICTAI.2019.00010"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-27T13:37:10+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: " 2019 IEEE 31st International Conference on Tools with Artificial Intelligence (ICTAI)"
publication_short: ""

abstract: "Symbolic execution is a powerful technique for bug finding and program testing. It is successful in finding bugs in real-world code. The core reasoning techniques use constraint solving, path exploration, and search, which are also the same techniques used in solving combinatorial problems, e.g., finite-domain constraint satisfaction problems (CSPs). We propose CSP instances as more challenging benchmarks to evaluate the effectiveness of the core techniques in symbolic execution. We transform CSP benchmarks into C programs suitable for testing the reasoning capabilities of symbolic execution tools. From a single CSP P, we transform P depending on transformation choice into different C programs. Preliminary testing with the KLEE, Tracer-X, and LLBMC tools show substantial runtime differences from transformation and solver choice. Our C benchmarks are effective in showing the limitations of existing symbolic execution tools. The motivation for this work is we believe that benchmarks of this form can spur the development and engineering of improved core reasoning in symbolic execution engines."

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

url_pdf: https://arxiv.org/pdf/2001.07914.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
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
