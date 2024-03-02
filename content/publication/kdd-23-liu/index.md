---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Learning Strong Graph Neural Networks with Weak Information"
authors: [Yixin Liu, Kaize Ding, Jianling Wang, Vincent Lee, Huan Liu, Shirui Pan]
date: 2023-08-06T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-16T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "29th SIGKDD Conference on Knowledge Discovery and Data Mining, KDD-23, 6 Aug 2023 – 10 Aug 2023, Long Beach, California, United States (CORE A*)"
publication_short: ""

abstract: "Graph Neural Networks (GNNs) have exhibited impressive performance in many graph learning tasks. Nevertheless, the performance of GNNs can deteriorate when the input graph data suffer from weak information, i.e., incomplete structure, incomplete features, and insufficient labels. Most prior studies, which attempt to learn from the graph data with a specific type of weak information, are far from effective in dealing with the scenario where diverse data deficiencies exist and mutually affect each other. To fill the gap, in this paper, we aim to develop an effective and principled approach to the problem of graph learning with weak information (GLWI). Based on the findings from our empirical analysis, we derive two design focal points for solving the problem of GLWI, i.e., enabling long-range propagation in GNNs and allowing information propagation to those stray nodes isolated from the largest connected component. Accordingly, we propose DPT, a dual-channel GNN framework that performs long-range information propagation not only on the input graph with incomplete structure, but also on a global graph that encodes global semantic similarities. We further develop a prototype contrastive alignment algorithm that aligns the class-level prototypes learned from two channels, such that the two different information propagation processes can mutually benefit from each other and the finally learned model can well handle the GLWI problem. Extensive experiments on eight real-world benchmark datasets demonstrate the effectiveness and efficiency of our proposed methods in various GLWI scenarios."

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

url_pdf: https://arxiv.org/pdf/2305.18457.pdf
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
