---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Cyclic label propagation for graph semi-supervised learning"
authors: [Zhao Li, Yixin Liu, Zhen Zhang, Shirui Pan, Jianliang Gao, Jiajun Bu]
date: 2021-06-24T09:36:47+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-24T09:36:47+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "World Wide Web"
publication_short: ""

abstract: "Graph neural networks (GNNs) have emerged as effective approaches for graph analysis, especially in the scenario of semi-supervised learning. Despite its success, GNN often suffers from over-smoothing and over-fitting problems, which affects its performance on node classification tasks. We analyze that an alternative method, the label propagation algorithm (LPA), avoids the aforementioned problems thus it is a promising choice for graph semi-supervised learning. Nevertheless, the intrinsic limitations of LPA on feature exploitation and relation modeling make propagating labels become less effective. To overcome these limitations, we introduce a novel framework for graph semi-supervised learning termed as Cyclic Label Propagation (CycProp for abbreviation), which integrates GNNs into the process of label propagation in a cyclic and mutually reinforcing manner to exploit the advantages of both GNNs and LPA. In particular, our proposed CycProp updates the node embeddings learned by GNN module with the augmented information by label propagation, while fine-tunes the weighted graph of label propagation with the help of node embedding in turn. After the model converges, reliably predicted labels and informative node embeddings are obtained with the LPA and GNN modules respectively. Extensive experiments on various real-world datasets are conducted, and the experimental results empirically demonstrate that the proposed CycProp model can achieve relatively significant gains over the state-of-the-art methods."

# Summary. An optional shortened abstract.
summary: ""

tags: [Graph neural networks]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2011.11860.pdf
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
