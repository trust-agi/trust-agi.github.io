---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Unraveling Privacy Risks of Individual Fairness in Graph Neural Networks"
authors: [He Zhang, Xingliang Yuan, Shirui Pan]
date: 2024-04-16T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-03-20T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "40th IEEE International Conference on Data Engineering (ICDE), April 16-19, 2024, Utrecht, Netherlands (CORE A*)"
publication_short: ""

abstract: "Graph neural networks (GNNs) have gained significant attraction due to their expansive real-world applications. To build trustworthy GNNs, two aspects - fairness and privacy - have emerged as critical considerations. Previous studies have separately examined the fairness and privacy aspects of GNNs, revealing their trade-off with GNN performance. Yet, the interplay between these two aspects remains unexplored. In this paper, we pioneer the exploration of the interaction between the privacy risks of edge leakage and the individual fairness of a GNN. Our theoretical analysis unravels that edge privacy risks unfortunately escalate when the nodes' individual fairness improves. Such an issue hinders the accomplishment of privacy and fairness of GNNs at the same time. To balance fairness and privacy, we carefully introduce fairness-aware loss reweighting based on influence function and privacy-aware graph structure perturbation modules within a fine-tuning mechanism. Experimental results underscore the effectiveness of our approach in achieving GNN fairness with limited performance compromise and controlled privacy risks. This work contributes to the comprehensively developing trustworthy GNNs by simultaneously addressing both fairness and privacy aspects."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks, privacy, fairness]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2301.12951.pdf
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
