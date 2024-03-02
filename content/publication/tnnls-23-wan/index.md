---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Boosting Graph Contrastive Learning via Adaptive Sampling"
authors: [Sheng Wan, Yibing Zhan, Shuo Chen, Shirui Pan, Jian Yang, Dacheng Tao, Chen Gong]
date: 2023-08-05T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-06-05T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Neural Networks and Learning Systems (TNNLS)"
publication_short: ""

abstract: "Contrastive Learning (CL) is a prominent technique for self-supervised representation learning, which aims to contrast semantically similar (i.e., positive) and dissimilar (i.e., negative) pairs of examples under different augmented views. Recently, CL has provided unprecedented potential for learning expressive graph representations without external supervision. In graph CL, the negative nodes are typically uniformly sampled from augmented views to formulate the contrastive objective. However, this uniform negative sampling strategy limits the expressive power of contrastive models. To be specific, not all the negative nodes can provide sufficiently meaningful knowledge for effective contrastive representation learning. In addition, the negative nodes that are semantically similar to the anchor are undesirably repelled from it, leading to degraded model performance. To address these limitations, in this paper, we devise an Adaptive Sampling strategy termed ‘AdaS’. The proposed AdaS framework can be trained to adaptively encode the importance of different negative nodes, so as to encourage learning from the most informative graph nodes. Meanwhile, an auxiliary polarization regularizer is proposed to suppress the adverse impacts of the false negatives and enhance the discrimination ability of AdaS. The experimental results on a variety of realworld datasets firmly verify the effectiveness of our AdaS in improving the performance of graph CL."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks, contrastive learning]
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
