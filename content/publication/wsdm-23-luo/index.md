---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Graph Sequential Neural ODE Process for Link Prediction on Dynamic and Sparse Graphs"
authors: [Linhao Luo, Reza Haffari, Shirui Pan]
date: 2023-02-27T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-10-18T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM International Conference on Web Search and Data Mining, WSDM-23, Feb 27, 2023 - Mar 3, 2023, Singapore (CORE A*)"
publication_short: ""

abstract: "Link prediction on dynamic graphs is an important task in graph mining. Existing approaches based on dynamic graph neural networks (DGNNs) typically require a significant amount of historical data (interactions over time), which is not always available in practice. The missing links over time, which is a common phenomenon in graph data, further aggravate the issue and thus create extremely sparse and dynamic graphs. To address this problem, we propose a novel method based on the neural process, called Graph Sequential Neural ODE Process (GSNOP). Specifically, GSNOP combines the advantage of the neural process and neural ordinary differential equation that models the link prediction on dynamic graphs as a dynamic-changing stochastic process. By defining a distribution over functions, GSNOP introduces the uncertainty to the predictions, making it generalize to more situations instead of overfitting to the sparse data. GSNOP is also agnostic to model structures that can be integrated with any DGNN to consider the chronological and geometrical information for link prediction. Extensive experiments on three dynamic graph datasets show that GSNOP can significantly improve the performance of existing DGNNs and outperform other neural process variants."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks, link prediction]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2211.08568.pdf
url_code: https://github.com/RManLuo/GSNOP
url_dataset:
url_poster: https://github.com/RManLuo/GSNOP/blob/master/WSDM-23-GSNOP-Poster.pdf
url_project:
url_slides: https://github.com/RManLuo/GSNOP/blob/master/WSDM-23-GSNOP-Slides.pdf
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
