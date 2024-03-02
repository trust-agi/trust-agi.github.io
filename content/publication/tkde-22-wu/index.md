---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Beyond low-pass filtering: Graph convolutional networks with automatic filtering"
authors: [Zonghan Wu, Shirui Pan, Guodong Long, Jing Jiang, Chengqi Zhang]
date: 2022-11-25T09:36:17+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-17T09:36:17+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Knowledge and Data Engineering (TKDE)"
publication_short: ""

abstract: "Graph convolutional networks are becoming indispensable for deep learning from graph-structured data. Most of the existing graph convolutional networks share two big shortcomings. First, they are essentially low-pass filters, thus the potentially useful middle and high frequency band of graph signals are ignored. Second, the bandwidth of existing graph convolutional filters is fixed. Parameters of a graph convolutional filter only transform the graph inputs without changing the curvature of a graph convolutional filter function. In reality, we are uncertain about whether we should retain or cut off the frequency at a certain point unless we have expert domain knowledge. In this paper, we propose Automatic Graph Convolutional Networks (AutoGCN) to capture the full spectrum of graph signals and automatically update the bandwidth of graph convolutional filters. While it is based on graph spectral theory, our AutoGCN is also localized in space and has a spatial form. Experimental results show that AutoGCN achieves significant improvement over baseline methods which only work as low-pass filters."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph convolutional networks]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2107.04755.pdf
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
