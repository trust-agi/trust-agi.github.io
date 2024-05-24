---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "GoLoG: Global-to-Local Decoupling Graph Network With Joint Optimization for Hyperspectral Image Classification"
authors: [Bing Yang, Hailiang Ye, Ming Li, Feilong Cao, Shirui Pan]
author_notes:
date: 2024-04-08T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-04-08T19:47:36+11:00

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Geoscience and Remote Sensing (TGRS)"
publication_short: ""

abstract: "Graph neural networks (GNNs) have a powerful ability to capture long-range spatial correlations in hyperspectral images (HSIs). However, existing GNN-based HSI classification methods are vulnerable to hand-crafted graphs, as the manner in which these graphs are constructed are often inappropriate and are likely to violate intrinsic graph properties, such as sparsity and low-rank. More importantly, the goal of HSI classification is to categorize each individual pixel into a land-cover class, but existing methods usually overuse global dependencies and ignore the importance of individualized spectral characteristics. Therefore, this article proposes a Global-to-Local decoupling Graph network (GoLoG) to conduct HSI classification in a global-to-local framework, which jointly optimizes the graph structure and network parameters guided by both intrinsic graph properties and classification loss. Specifically, a novel global-to-local network framework with successive global and local graph convolutional stages is constructed. By decoupling global and local stages, global contextual information can be exploited, and the individualized information of each hyperspectral pixel can be emphasized for HSI classification. Second, a sparse and low-rank graph structure learning model is proposed to refine and renovate the initial-construct graph. Finally, to unify graph structure learning and network training, a joint alternating update algorithm is introduced to jointly optimize the sparse and low-rank graph structure learning model and the global-to-local network framework. Extensive experiments demonstrate that the proposed GoLoG has obvious advantages compared with other state-of-the-art HSI classification methods."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks]
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
