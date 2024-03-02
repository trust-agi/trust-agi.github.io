---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Dual Space Graph Contrastive Learning"
authors: [Haoran Yang, Hongxu Chen, Shirui Pan, Lin Li, Philip S Yu, Guandong Xu]
date: 2022-04-25T09:36:17+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-01-14T09:36:17+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The Web Conference (WWW-2022)"
publication_short: ""

abstract: "Unsupervised graph representation learning has emerged as a powerful tool to address real-world problems and achieves huge success in the graph learning domain. Graph contrastive learning is one of the unsupervised graph representation learning methods, which recently attracts attention from researchers and has achieved state-of-the-art performances on various tasks. The key to the success of graph contrastive learning is to construct proper contrasting pairs to acquire the underlying structural semantics of the graph. However, this key part is not fully explored currently, most of the ways to generate contrasting pairs focus on augmenting or perturbating graph structures to obtain different views of the input graph. But such strategies could degrade the performances via adding noise into the graph, which may narrow down the field of the applications of graph contrastive learning. In this paper, we propose a novel graph contrastive learning method, namely Dual Space Graph Contrastive (DSGC) Learning, to conduct graph contrastive learning among views generated in different spaces including the hyperbolic space and the Euclidean space. Since both spaces have their own advantages to represent graph data in the embedding spaces, we hope to utilize graph contrastive learning to bridge the spaces and leverage advantages from both sides. The comparison experiment results show that DSGC achieves competitive or better performances among all the datasets. Plus, we conduct extensive experiments to analyze the impact of different graph encoders on DSGC, giving insights about how to better leverage the advantages of contrastive learning between different spaces."

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

url_pdf: https://arxiv.org/pdf/2201.07409.pdf
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
