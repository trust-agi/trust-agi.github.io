---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Exploring Relational Semantics for Inductive Knowledge Graph Completion"
authors: [Changjian Wang, Xiaofei Zhou, Shirui Pan, Linhua Dong, Zeliang Song, Ying Sha]
date: 2022-02-22T09:36:17+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-12-10T09:36:17+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "AAAI Conference on Artificial Intelligence (AAAI-2022)"
publication_short: ""

abstract: "Knowledge graph completion (KGC) aims to infer missing information in incomplete knowledge graphs (KGs). Most previous works only consider the transductive scenario where entities are existing in KGs, which cannot work effectively for the inductive scenario containing emerging entities. Recently some graph neural network-based methods have been proposed for inductive KGC by aggregating neighborhood information to capture some uncertainty semantics from the neighboring auxiliary triples. But these methods ignore the more general relational semantics underlying all the known triples that can provide richer information to represent emerging entities so as to satisfy the inductive scenario. In this paper, we propose a novel model called CFAG, which utilizes two granularity levels of relational semantics in a coarse-grained aggregator (CG-AGG) and a fine-grained generative adversarial net (FG-GAN), for inductive KGC. The CG-AGG firstly generates entity representations with multiple semantics through a hypergraph neural network-based global aggregator and a graph neural network-based local aggregator, and the FG-GAN further enhances entity representations with specific semantics through conditional generative adversarial nets. Experimental results on benchmark datasets show that our model outperforms state-of-the-art models for inductive KGC."

# Summary. An optional shortened abstract.
summary: ""

tags: [knowledge graphs]
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
