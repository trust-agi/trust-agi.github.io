---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Robust Graph Representation Learning for Local Corruption Recovery"
authors: [Bingxin Zhou, Yuanhong Jiang, Yuguang Wang, Jingwei Liang, Junbin Gao, Shirui Pan, Xiaoqun Zhang]
date: 2023-04-30T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-02-25T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The ACM Web Conference 2023, WWW-23, Austin, Texas, USA, April 30 - May 4, 2023 (CORE A*)"
publication_short: ""

abstract: "The performance of graph representation learning is affected by the quality of graph input. While existing research usually pursues a globally smoothed graph embedding, we believe the rarely observed anomalies are as well harmful to an accurate prediction. This work establishes a graph learning scheme that automatically detects (locally) corrupted feature attributes and recovers robust embedding for prediction tasks. The detection operation leverages a graph autoencoder, which does not make any assumptions about the distribution of the local corruptions. It pinpoints the positions of the anomalous node attributes in an unbiased mask matrix, where robust estimations are recovered with sparsity promoting regularizer. The optimizer approaches a new embedding that is sparse in the framelet domain and conditionally close to input observations. Extensive experiments are provided to validate our proposed model can recover a robust graph representation from black-box poisoning and achieve excellent performance."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2202.04936.pdf
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
