---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "CGMN: A Contrastive Graph Matching Network for Self-Supervised Graph Similarity Learning"
authors: [Di Jin, Luzhi Wang, Yizhen Zheng, Xiang Li, Fei Jiang, Wei Lin, Shirui Pan]
date: 2022-07-23T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-04-20T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "31st International Joint Conference on Artificial Intelligence (IJCAI-22), July 23-29, 2022 Messe Wien, Vienna, Austria"
publication_short: ""

abstract: "Graph similarity learning refers to calculating the similarity score between two graphs, which is required in many realistic applications, such as visual tracking, graph classification, and collaborative filtering. As most of the existing graph neural networks yield effective graph representations of a single graph, little effort has been made for jointly learning two graph representations and calculating their similarity score. In addition, existing unsupervised graph similarity learning methods are mainly clustering-based, which ignores the valuable information embodied in graph pairs. To this end, we propose a contrastive graph matching network (CGMN) for self-supervised graph similarity learning in order to calculate the similarity between any two input graph objects. Specifically, we generate two augmented views for each graph in a pair respectively. Then, we employ two strategies, namely cross-view interaction and cross-graph interaction, for effective node representation learning. The former is resorted to strengthen the consistency of node representations in two views. The latter is utilized to identify node differences between different graphs. Finally, we transform node representations into graph-level representations via pooling operations for graph similarity computation. We have evaluated CGMN on eight real-world datasets, and the experiment results show that the proposed new approach is superior to the state-of-the-art methods in graph similarity learning downstream tasks."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks, graph matching, self-supervised learning]
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
