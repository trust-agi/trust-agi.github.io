---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Simple and Efficient Heterogeneous Graph Neural Network"
authors: [Xiaocheng Yang, Mingyu Yan, Shirui Pan, Xiaochun Ye, Dongrui Fan]
date: 2023-02-27T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-11-09T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In Proceedings of AAAI Conference on Artificial Intelligence (AAAI), AAAI-23, Washington, DC, USA, February 7-14, 2023 (CORE A*)"
publication_short: ""

abstract: "Heterogeneous graph neural networks (HGNNs) deliver the powerful capability to embed rich structural and semantic information of a heterogeneous graph into low-dimensional node representations. Existing HGNNs usually learn to embed information using hierarchy attention mechanism and repeated neighbor aggregation, suffering from unnecessary complexity and redundant computation. This paper proposes Simple and Efficient Heterogeneous Graph Neural Network (SeHGNN) which reduces this excess complexity through avoiding overused node-level attention within the same relation and pre-computing the neighbor aggregation in the pre-processing stage. Unlike previous work, SeHGNN utilizes a light-weight parameter-free neighbor aggregator to learn structural information for each metapath, and a transformer-based semantic aggregator to combine semantic information across metapaths for the final embedding of each node. As a result, SeHGNN offers the simple network structure, high prediction accuracy, and fast training speed. Extensive experiments on five real-world heterogeneous graphs demonstrate the superiority of SeHGNN over the state-of-the-arts on both the accuracy and training speed. Codes are available at https://github.com/ICT-GIMLab/SeHGNN."

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

url_pdf: https://arxiv.org/pdf/2207.02547.pdf
url_code: https://github.com/ICT-GIMLab/SeHGNN
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
projects: [Graph Neural Networks]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
