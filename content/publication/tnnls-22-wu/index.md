---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "TraverseNet: Unifying Space and Time in Message Passing for Traffic Forecasting"
authors: [Zonghan Wu, Da Zheng, Shirui Pan, Quan Gan, Guodong Long, George Karypis]
date: 2022-11-25T09:36:17+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-17T09:36:17+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Neural Networks and Learning Systems (TNNLS)"
publication_short: ""

abstract: "This paper aims to unify spatial dependency and temporal dependency in a non-Euclidean space while capturing the inner spatial-temporal dependencies for traffic data. For spatial-temporal attribute entities with topological structure, the space-time is consecutive and unified while each node’s current status is influenced by its neighbors’ past states over variant periods of each neighbor. Most spatial-temporal neural networks for traffic forecasting study spatial dependency and temporal correlation separately in processing, gravely impaired the spatial-temporal integrity, and ignore the fact that the neighbors’ temporal dependency period for a node can be delayed and dynamic. To model this actual condition, we propose TraverseNet, a novel spatial-temporal graph neural network, viewing space and time as an inseparable whole, to mine spatial-temporal graphs while exploiting the evolving spatial-temporal dependencies for each node via message traverse mechanisms. Experiments with ablation and parameter studies have validated the effectiveness of the proposed TraverseNet, and the detailed implementation can be found from https://github.com/nnzhan/TraverseNet."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph convolutional networks, traffic forecasting]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2109.02474.pdf
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
