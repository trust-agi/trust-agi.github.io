---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Normalizing Flow-based Neural Process for Few-Shot Knowledge Graph Completion"
authors: [Linhao Luo, Reza Haffari, Yuan-Fang Li, Shirui Pan]
date: 2023-07-23T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-04-06T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 46th International ACM SIGIR Conference on Research and Development in Information Retrieval, SIGIR-23, 23-27 July, 2023, Taipei, Taiwan. (CORE A*)"
publication_short: ""

abstract: "Knowledge graphs (KGs), as a structured form of knowledge representation, have been widely applied in the real world. Recently, few-shot knowledge graph completion (FKGC), which aims to predict missing facts for unseen relations with few-shot associated facts, has attracted increasing attention from practitioners and researchers. However, existing FKGC methods are based on metric learning or meta-learning, which often suffer from out-of-distribution and overfitting problems. Meanwhile, they are incompetent at estimating the uncertainty, which is critically important as model predictions could be very unreliable in few-shot setting. Furthermore, most of them cannot handle complex relations and ignore path information in KGs, which largely limits their performance. In this paper, we propose a novel normalizing flow-based neural process for few-shot knowledge graph completion (NP-FKGC). Specifically, we unify the normalizing flow and neural process to model the complex distribution of KG completion functions. This offers a novel way to predict facts for few-shot relations while estimating the uncertainty in predictions. Then we propose a stochastic ManifoldE decoder to incorporate the neural process and handle complex relations in the few-shot setting. To further improve performance, we introduce an attentive relation path-based graph neural network to capture path information in KGs. Extensive experiments on three public datasets demonstrate that our method significantly outperforms the existing FKGC methods and achieves the state-of-the-art performance."

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

url_pdf: https://arxiv.org/pdf/2304.08183.pdf
url_code: https://github.com/RManLuo/NP-FKGC
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
