---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Discrete Embedding for Attributed Graphs"
authors: [Hong Yang, Ling Chen, Shirui Pan, Haishuai Wang, Peng Zhang]
date: 2022-01-22T19:56:22+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-15T19:56:22+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Pattern Recognition"
publication_short: ""

abstract: "Attributed graphs refer to graphs where both node links and node attributes are observable for analysis. Attributed graph embedding enables joint representation learning of node links and node attributes. Different from classical graph embedding methods such as Deepwalk and node2vec that first project node links into low-dimensional vectors which are then linearly concatenated with node attribute vectors as node representation, attributed graph embedding fully explores data dependence between node links and attributes by either using node attributes as class labels to supervise structure learning from node links, or reversely using node links to supervise the learning from node attributes. However, existing attributed graph embedding models are designed in continuous Euclidean spaces which often introduce data redundancy and impose challenges to storage and computation costs. In this paper, we study a new problem of discrete embedding for attributed graphs that can learn succinct node representations. Specifically, we present a Binarized Attributed Network Embedding model (BANE for short) to learn binary node representation by factorizing a Weisfeiler-Lehman proximity matrix under the constraint of binary node representation. Furthermore, based on BANE, we propose a new Low-bit Quantization for Attributed Network Representation learning model (LQANR for short) to learn even more compact node representation of bit-width values. Theoretical analysis and empirical studies on real-world datasets show that the new discrete embedding models outperform benchmark methods."

# Summary. An optional shortened abstract.
summary: ""

tags: [Network Embedding]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
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
