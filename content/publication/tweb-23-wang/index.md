---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Contrastive Graph Similarity Networks"
authors: [Luzhi Wang, Yizhen Zheng, Di Jin, Fuyi Li, Yongliang Qiao, Shirui Pan]
date: 2023-01-30T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-01-30T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on the Web"
publication_short: ""

abstract: "Graph similarity learning is a significant and fundamental issue in the theory and analysis of graphs, which has been applied in a variety of fields, including object tracking, recommender systems, similarity search, etc. Recent methods for graph similarity learning that utilize deep learning typically share two deficiencies: (1) they leverage graph neural networks as backbones for learning graph representations but have not well captured the complex information inside data, and (2) they employ a cross-graph attention mechanism for graph similarity learning, which is computationally expensive. Taking these limitations into consideration, a method for graph similarity learning is devised in this study, namely, Contrastive Graph Similarity Network (CGSim). To enhance graph similarity learning, CGSim makes use of the complementary information of two input graphs and captures pairwise relations in a contrastive learning framework. By developing a dual contrastive learning module with a node-graph matching and a graph-graph matching mechanism, our method significantly reduces the quadratic time complexity for cross-graph interaction modeling to linear time complexity. Jointly learning in an end-to-end framework, the graph representation embedding module and the well-designed contrastive learning module can be beneficial to one another. A comprehensive series of experiments indicate that CGSim outperforms state-of-the-art baselines on six datasets and significantly reduces the computational cost, which demonstrates our CGSim model’s superiority over other baselines."

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
projects: [Graph Neural Networks]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
