---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Towards Unsupervised Deep Graph Structure Learning"
authors: [Yixin Liu, Yu Zheng, Daokun Zhang, Hongxu Chen, Hao Peng, Shirui Pan]
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

abstract: "In recent years, graph neural networks (GNNs) have emerged as a successful tool in a variety of graph-related applications. However, the performance of GNNs can be deteriorated when noisy connections occur in the original graph structures; besides, the dependence on explicit structures prevents GNNs from being applied to general unstructured scenarios. To address these issues, recently emerged deep graph structure learning (GSL) methods propose to jointly optimize the graph structure along with GNN under the supervision of a node classification task. Nonetheless, these methods focus on a supervised learning scenario, which leads to several problems, i.e., the reliance on labels, the bias of edge distribution, and the limitation on application tasks. In this paper, we propose a more practical GSL paradigm, unsupervised graph structure learning, where the learned graph topology is optimized by data itself without any external guidance (i.e., labels). To solve the unsupervised GSL problem, we propose a novel StrUcture Bootstrapping contrastive LearnIng fraMEwork (SUBLIME for abbreviation) with the aid of self-supervised contrastive learning. Specifically, we generate a learning target from the original data as an “anchor graph”, and use a contrastive loss to maximize the agreement between the anchor graph and the learned graph. To provide persistent guidance, we design a novel bootstrapping mechanism that upgrades the anchor graph with learned structures during model learning. We also design a series of graph learners and post-processing schemes to model the structures to learn. Extensive experiments on eight benchmark datasets demonstrate the significant effectiveness of our proposed SUBLIME and high quality of the optimized graphs."

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
