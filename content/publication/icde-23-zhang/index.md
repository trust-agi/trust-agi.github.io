---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "TxAllo: Dynamic Transaction Allocation in Sharded Blockchain Systems"
authors: [Yuanzhe Zhang, Shirui Pan, Jiangshan Yu]
date: 2023-04-03T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-11-09T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Data Engineering, ICDE-23, Anaheim, California, United States, April 3 - 7, 2022 (CORE A*)"
publication_short: ""

abstract: "The scalability problem has been one of the most significant barriers limiting blockchain adoption. Blockchain sharding is a promising approach to this problem. However, the sharding mechanism introduces a significant number of cross-shard transactions, which are expensive to process. This paper presents TxAllo to significantly reduce the number of cross-shard transactions and to improve blockchain scalability. In particular, we explore and define the transaction allocation problem and convert it to the community detection problem on a graph. TxAllo is a deterministic scheme to dynamically infer the allocation of accounts and their associated transactions with optimal system throughput. It considers both the number of cross-shard transactions and the workload balance among shards with fast execution. We evaluate the performance of TxAllo on an Ethereum dataset containing over 91 million transactions. Our evaluation results show that for a blockchain with 60 shards, TxAllo reduces the cross-shard transaction ratio from 98% (by using traditional hash-based allocation) to about 12%. In addition, we enable an adaptive model of TxAllo to perform updates according to the previous allocation results and the newly included transactions. Compared with other methods, the execution time of TxAllo is almost negligible. For example, when updating the allocation every hour, the execution of TxAllo only takes 0.5 seconds on average, whereas other concurrent works, such as Brokerchain (INFOCOM'22) leveraging the classic METIS method, require 422 seconds."

# Summary. An optional shortened abstract.
summary: ""

tags: [blockchain]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2212.11584.pdf
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
