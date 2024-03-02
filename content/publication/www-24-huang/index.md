---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Cost-effective Data Labelling for Graph Neural Networks"
authors: [Shixun Huang, Ge Lee, Zhifeng Bao, Shirui Pan]
date: 2024-05-13T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-01-20T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Web Conference 2024 (WWW), May 13 - 17, 2024, Singapore, Singapore (CORE A*)"
publication_short: ""

abstract: "Active learning (AL), that aims to label limited data samples to effectively train the model, stands as a very cost-effective data labelling strategy in machine learning. Given the state-of-the-art performance GNNs have achieved in graph-based tasks, it is critical to design proper AL methods for graph neural networks (GNNs). However, existing GNN-based AL methods require considerable supervised information to guide the AL process, such as the GNN model to use, and initially labelled nodes and labels of newly selected nodes. Such dependency on supervised information limits both flexibility and scalabilty. In this paper, we propose an unsupervised, scalable and flexible AL method – it incurs low memory footprints and time cost, is flexible to the choice of underlying GNNs, and operates without requiring GNN-model-specific knowledge or labels of selected nodes. Specifically, we leverage the commonality of existing GNNs to reformulate the unsupervised AL problem as the Aggregation Involvement Maximization (AIM) problem. The objective of AIM is to maximize the involvement or participation of all nodes during the feature aggregation process of GNNs for nodes to be labelled. In this way, the aggregated features of labelled nodes can be diversified to a large extent, thereby benefiting the training of feature transformation matrices which are major trainable components in GNNs. We prove that the AIM problem is NP-hard and propose an efficient solution with theoretical guarantees. Extensive experiments on public datasets demonstrate the effectiveness, scalability and flexibility of our method."

# Summary. An optional shortened abstract.
summary: ""

tags: [active learning, graph neural networks]
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
