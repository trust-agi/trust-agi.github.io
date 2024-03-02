---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Towards Graph Self-Supervised Learning with Contrastive Adjusted Zooming"
authors: [Yizhen Zheng, Ming Jin, Shirui Pan, Yuan-Fang Li, Hao Peng, Ming Li, Zhao Li]
date: 2022-11-25T09:36:17+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-30T09:36:17+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: " IEEE Transactions on Neural Networks and Learning Systems (TNNLS)"
publication_short: ""

abstract: "Graph representation learning (GRL) is critical for graph-structured data analysis. However, most of the existing graph neural networks (GNNs) heavily rely on labeling information, which is normally expensive to obtain in the real world. Existing unsupervised GRL methods suffer from certain limitations, such as the heavy reliance on monotone contrastiveness and limited scalability. To overcome the aforementioned problems, in light of the recent advancements in graph contrastive learning, we introduce a novel self-supervised graph representation learning algorithm via Graph Contrastive Adjusted Zooming, namely G-Zoom, to learn node representations by leveraging the proposed adjusted zooming scheme. Specifically, this mechanism enables G-Zoom to explore and extract self-supervision signals from a graph from multiple scales: micro (i.e., node-level), meso (i.e., neighbourhood-level), and macro (i.e., subgraph-level). Firstly, we generate two augmented views of the input graph via two different graph augmentations. Then, we establish three different contrastiveness on the above three scales progressively, from node, neighbouring, to subgraph level, where we maximize the agreement between graph representations across scales. While we can extract valuable clues from a given graph on the micro and macro perspectives, the neighbourhood-level contrastiveness offers G-Zoom the capability of a customizable option based on our adjusted zooming scheme to manually choose an optimal viewpoint that lies between the micro and macro perspectives to better understand the graph data. Additionally, to make our model scalable to large graphs, we employ a parallel graph diffusion approach to decouple model training from the graph size. We have conducted extensive experiments on real-world datasets, and the results demonstrate that our proposed model outperforms state-of-the-art methods consistently."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks, self-supervised learning]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2111.10698
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
