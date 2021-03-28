---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Synergistic debug-repair of heap manipulations"
authors: ["Sahil Verma", "Subhajit Roy"]
date: 2017-08-21
doi: "10.1145/3106237.3106263"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-27T13:37:02+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 2017 11th Joint Meeting on Foundations of Software Engineering"
publication_short: ""

abstract: "We present Wolverine, an integrated Debug-Repair environment for heap manipulating programs. Wolverine facilitates stepping through a concrete program execution, provides visualizations of the abstract program states (as box-and-arrow diagrams) and integrates a novel, proof-directed repair algorithm to synthesize repair patches. To provide a seamless environment, Wolverine supports 'hot-patching' of the generated repair patches, enabling the programmer to continue the debug session without requiring an abort-compile-debug cycle. We also propose new debug-repair possibilities, 'specification refinement' and 'specification slicing' made possible by Wolverine. We evaluate our framework on 1600 buggy programs (generated using fault injection) on a variety of data-structures like singly, doubly and circular linked-lists, Binary Search Trees, AVL trees, Red-Black trees and Splay trees; Wolverine could repair all the buggy instances within reasonable time (less than 5 sec in most cases). We also evaluate Wolverine on 247 (buggy) student submissions; Wolverine could repair more than 80% of programs where the student had made a reasonable attempt."

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

url_pdf: files/papers/fse17-mainid118.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides: presentation.pdf
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
