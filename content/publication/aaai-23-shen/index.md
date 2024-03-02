---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Neighbor Contrastive Learning on Learnable Graph Augmentation"
authors: [Xiao Shen, Dewang sun, Shirui Pan, Xi Zhou, and Laurence T. Yang]
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

abstract: "Recent years, graph contrastive learning (GCL), which aims to learn representations from unlabeled graphs, has made great progress. However, the existing GCL methods mostly adopt human-designed graph augmentations, which are sensitive to various graph datasets. In addition, the contrastive losses originally developed in computer vision have been directly applied to graph data, where the neighboring nodes are regarded as negatives and consequently pushed far apart from the anchor. However, this is contradictory with the homophily assumption of networks that connected nodes often belong to the same class and should be close to each other. In this work, we propose an end-to-end automatic GCL method, named NCLA to apply neighbor contrastive learning on learnable graph augmentation. Several graph augmented views with adaptive topology are automatically learned by the multi-head graph attention mechanism, which can be compatible with various graph datasets without prior domain knowledge. In addition, a neighbor contrastive loss is devised to allow multiple positives per anchor by taking network topology as the supervised signals. Both augmentations and embeddings are learned end-to-end in the proposed NCLA. Extensive experiments on the benchmark datasets demonstrate that NCLA yields the state-of-the-art node classification performance on self-supervised GCL and even exceeds the supervised ones, when the labels are extremely limited."

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

url_pdf: https://arxiv.org/pdf/2301.01404.pdf
url_code: https://github.com/shenxiaocam/NCLA
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
