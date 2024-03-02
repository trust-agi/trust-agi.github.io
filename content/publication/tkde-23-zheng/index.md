---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Spatio-Temporal Joint Graph Convolutional Networks for Traffic Forecasting"
authors: [Chuanpan Zheng, Xiaoliang Fan, Shirui Pan, Haibing Jin, Zhaopeng Peng, Zonghan Wu, Cheng Wang, Philip S. Yu]
date: 2023-06-05T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-06-05T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Knowledge and Data Engineering (TKDE)"
publication_short: ""

abstract: "Recent studies focus on formulating the traffic forecasting as a spatio-temporal graph modeling problem. They typically construct a static spatial graph at each time step and then connect each node with itself between adjacent time steps to construct the spatio-temporal graph. In such a graph, the correlations between different nodes at different time steps are not explicitly reflected, which may restrict the learning ability of graph neural networks. Meanwhile, those models ignore the dynamic spatio-temporal correlations among nodes as they use the same adjacency matrix at different time steps. To overcome these limitations, we propose a Spatio-Temporal Joint Graph Convolutional Networks (STJGCN) for traffic forecasting over several time steps ahead on a road network. Specifically, we construct both pre-defined and adaptive spatio-temporal joint graphs (STJGs) between any two time steps, which represent comprehensive and dynamic spatio-temporal correlations. We further design dilated causal spatio-temporal joint graph convolution layers on STJG to capture the spatio-temporal dependencies from distinct perspectives with multiple ranges. A multi-range attention mechanism is proposed to aggregate the information of different ranges. Experiments on four public traffic datasets demonstrate that STJGCN is computationally efficient and outperforms 11 state-of-the-art baseline methods."

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

url_pdf: https://arxiv.org/pdf/2111.13684.pdf
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
