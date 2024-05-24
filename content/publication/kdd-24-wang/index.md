---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "The Heterophily Snowflake Hypothesis: Training and Empowering GNN for Heterophilic Graphs"
authors: [Kun Wang, Guibin Zhang, Xinnan Zhang, Junfeng Fang, Xun Wu, Guohao Li, Shirui Pan, Wei Huang, Yuxuan Liang]
date: 2024-08-25T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-05-15T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), Aug 25, 2024 - Aug 29, 2024, Barcelona, Spain (CORE A*)"
publication_short: ""

abstract: "Graph Neural Networks (GNNs) have become pivotal tools for a range of graph-based learning tasks. Notably, most current GNN architectures operate under the assumption of homophily, whether explicitly or implicitly. While this underlying assumption is frequently adopted, it is not universally applicable, which can result in potential shortcomings in learning effectiveness. In this paper, for the first time, we transfer the prevailing concept of 'one node one receptive field' to the heterophilic graph. By constructing a proxy label predictor, we enable each node to possess a latent prediction distribution, which assists connected nodes in determining whether they should aggregate their associated neighbors. Ultimately, every node can have its own unique aggregation hop and pattern, much like each snowflake is unique and possesses its own characteristics. Based on observations, we innovatively introduce the Heterophily Snowflake Hypothesis and provide an open source to guide and facilitate research on heterophilic graphs and beyond.We conduct comprehensive experiments including (1) main results on 10 graphs with varying heterophily ratios across 10 backbones; (2) scalability on various deep GNN backbones (SGC, JKNet, etc.) across various large number of layers (2,4,6,8,16,32 layers); (3) comparison with conventional snowflake hypothesis; (4) efficiency comparison with existing graph pruning algorithms. Our observations show that our framework acts as a versatile operator for diverse tasks. It can be integrated into various GNN frameworks, boosting performance in-depth and offering an explainable approach to choosing the optimal network depth."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural network]
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
