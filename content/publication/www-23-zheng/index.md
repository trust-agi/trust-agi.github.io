---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Auto-HeG: Automated Graph Neural Network on Heterophilic Graphs"
authors: [Xin Zheng, Miao Zhang, Chunyang Chen, Qin Zhang, Chuan Zhou, Shirui Pan]
date: 2023-04-30T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-02-25T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The ACM Web Conference 2023, WWW-23, Austin, Texas, USA, April 30 - May 4, 2023 (CORE A*)"
publication_short: ""

abstract: "Graph neural architecture search (NAS) has gained popularity in automatically designing powerful graph neural networks (GNNs) with relieving human efforts. However, existing graph NAS methods mainly work under the homophily assumption. In contrast, heterophily, which shares an opposite property of graph data to homophily, exists widely in various real-world applications, eg, online social networks and transactions. Despite its vital role in the web socio-economic system, automated heterophilic graph learning with NAS is still a research blank to be filled in. Due to the complexity and variety of heterophilic graphs, the critical challenge of heterophilic graph NAS mainly lies in developing the heterophily-specific search space and strategy. Therefore, in this paper, we propose a novel automated graph neural network on heterophilic graphs, namely Auto-HeG, to automatically build heterophilic GNN models with expressive learning abilities. Specifically, Auto-HeG incorporates heterophily into all stages of automatic heterophilic graph learning, including search space design, supernet training, and architecture selection. Through the diverse message-passing scheme with joint micro-level and macro-level designs, we first build a comprehensive heterophilic GNN search space, enabling Auto-HeG to integrate complex and various heterophily of graphs. With a progressive supernet training strategy, we dynamically shrink the initial search space according to layer-wise variation of heterophily, resulting in a compact and efficient supernet. Taking a heterophily-aware distance criterion as the guidance, we conduct heterophilic architecture selection in the leave-one-out pattern, so that specialized and expressive heterophilic GNN architectures can be derived. Extensive experiments illustrate the superiority of Auto-HeG in developing excellent heterophilic GNNs to human-designed models and graph NAS models."

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

url_pdf: https://arxiv.org/pdf/2302.12357.pdf
url_code: https://github.com/GRAND-Lab/Auto-HeG
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
