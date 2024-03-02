---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Towards Few-shot Inductive Link Prediction on Knowledge Graphs: A Relational Anonymous Walk-guided Neural Process Approach"
authors: [Zicheng Zhao, Linhao Luo, Shirui Pan, Quoc Viet Hung Nguyen, Chen Gong]
date: 2023-09-18T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-06T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases, ECML/PKDD, September 18 -22 2023, Turin, Italy (CORE A)"
publication_short: ""

abstract: "Few-shot inductive link prediction on knowledge graphs (KGs) aims to predict missing links for unseen entities with few-shot links observed. Previous methods are limited to transductive scenarios, where entities exist in the knowledge graphs, so they are unable to handle unseen entities. Therefore, recent inductive methods utilize the sub-graphs around unseen entities to obtain the semantics and predict links inductively. However, in the few-shot setting, the sub-graphs are often sparse and cannot provide meaningful inductive patterns. In this paper, we propose a novel relational anonymous walk-guided neural process for few-shot inductive link prediction on knowledge graphs, denoted as RawNP. Specifically, we develop a neural process-based method to model a flexible distribution over link prediction functions. This enables the model to quickly adapt to new entities and estimate the uncertainty when making predictions. To capture general inductive patterns, we present a relational anonymous walk to extract a series of relational motifs from few-shot observations. These motifs reveal the distinctive semantic patterns on KGs that support inductive predictions. Extensive experiments on typical benchmark datasets demonstrate that our model derives new state-of-the-art performance."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks, knowledge graphs]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2307.01204.pdf
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
