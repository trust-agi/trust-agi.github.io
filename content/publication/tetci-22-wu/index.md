---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Attraction and Repulsion: Unsupervised Domain Adaptive Graph Contrastive Learning Network"
authors: [Man Wu, Shirui Pan, Xingquan Zhu]
date: 2022-05-10T09:36:17+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-02-10T09:36:17+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Emerging Topics in Computational Intelligence (TETCI)"
publication_short: ""

abstract: "Graph convolutional networks (GCNs) are important techniques for many graph related analytics tasks. To date, most GCNs are designed for a single domain (graph) and therefore incapable of transferring knowledge from/to different domains (graphs), due to the inherent challenges in both graph representation learning and domain adaptation across graph domains. This paper proposes a novel Graph Contrastive Learning Network (GCLN) for unsupervised domain adaptive graph learning. The key innovation is to enforce attraction and repulsion forces within each single graph domain, and across two graph domains. Within each graph, an attraction force encourages local patch node features to be similar to global representation of the entire graph, whereas a repulsion force will repel node features so they can separate network from its permutations (i.e.  domain-specific graph contrastive learning). Across two graph domains, an attraction force encourages node features from two domains to be largely consistent, whereas a repulsion force ensures features are discriminative to differentiate graph domains (i.e. cross-domain graph contrastive learning). The within- and cross-domain graph contrastive learning is carried out by optimizing an objective function, which combines source classifier loss, domain classifier loss, target classifier loss, domain-specific contrastive loss, and cross-domain contrastive loss. As a result, feature learning from graphs are facilitated using knowledge transferred between graphs. Experiments on real-world datasets demonstrate that our method outperforms state-of-the-art graph neural network algorithms."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks, domain adaptation]
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
