---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "PREM: A Simple Yet Effective Approach for Node-Level Graph Anomaly Detection"
authors: [Junjun Pan, Yixin Liu, Yizhen Zheng, Shirui Pan]
date: 2023-12-01T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-09-20T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference of Data Mining 2023 (ICDM 2023), December 1-3, 2023, Shanghai, China (CORE A*)"
publication_short: ""

abstract: "Node-level graph anomaly detection (GAD) plays a critical role in identifying anomalous nodes from graph-structured data in various domains such as medicine, social networks, and e-commerce. However, challenges have arisen due to the diversity of anomalies and the dearth of labeled data. Existing methodologies - reconstruction-based and contrastive learning - while effective, often suffer from efficiency issues, stemming from their complex objectives and elaborate modules. To improve the efficiency of GAD, we introduce a simple method termed PREprocessing and Matching (PREM for short). Our approach streamlines GAD, reducing time and memory consumption while maintaining powerful anomaly detection capabilities. Comprising two modules - a pre-processing module and an ego-neighbor matching module - PREM eliminates the necessity for message-passing propagation during training, and employs a simple contrastive loss, leading to considerable reductions in training time and memory usage. Moreover, through rigorous evaluations of five real-world datasets, our method demonstrated robustness and effectiveness. Notably, when validated on the ACM dataset, PREM achieved a 5% improvement in AUC, a 9-fold increase in training speed, and sharply reduce memory usage compared to the most efficient baseline."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks, anomaly detection]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2310.11676.pdf
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
