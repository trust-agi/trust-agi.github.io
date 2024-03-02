---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Ultrahyperbolic Knowledge Graph Embeddings"
authors: [Bo Xiong, Shichao Zhu, Mojtaba Nayyeri, Chengjin Xu, Shirui Pan, Chuan Zhou, Steffen Staab]
date: 2022-08-14T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-05-19T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, KDD-22, Washington DC, Aug 14, 2022 - Aug 18, 2022."
publication_short: ""

abstract: "Recent knowledge graph (KG) embeddings have been advanced by the hyperbolic geometry due to its superior capability for representing hierarchies. The real-world KGs, however, are usually organized not uniformly, rather in a heterogeneous way, i.e., a KG is a mixture of multiple distinct hierarchies and non-hierarchical structures (e.g., cycles). A single homogeneous (either Euclidean or hyperbolic) geometry is not sufficient for representing such heterogeneous structures of KGs. To capture the heterogeneous structures of KGs, we present an Ultrahyperbolic KG Embedding (UltraE) in a pseudo-Riemannian manifold that seamlessly interleaves hyperbolic and spherical submanifolds that can naturally capture different graph structures. In particular, we consider the pseudo-hyperboloid of signature (p,q) and model relations as pseudo-orthogonal transformations that are isometries preserving the pseudo-Riemannian bilinear form. We derive a linearly complex relational parameterization by decomposing the quadratic pseudo-orthogonal transformation into various geometric operators (i.e., rotation, reflection, and translation), allowing for simultaneously modeling heterogeneous geometry as well as complex logical patterns including symmetry, anti-symmetry, inversion, and composition relations. We theoretically show the expressiveness of UltraE and discuss its connection to some existing Euclidean and hyperbolic methods. Experimental results on standard KG benchmarks show that UltraE outperforms previous Euclidean- and hyperbolic-based approaches."

# Summary. An optional shortened abstract.
summary: ""

tags: [knowledge graph embedding]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2206.00449.pdf
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
