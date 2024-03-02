---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Predicting Best-Selling New Products in a Major Promotion Campaign through Graph Convolutional Networks"
authors: [Chaojie Li, Wensen Jiang, Yin Yang, Shirui Pan, Lijie Guo, Gang Huang]
date: 2022-05-30T09:36:17+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-02-24T09:36:17+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Neural Networks and Learning Systems (TNNLS)"
publication_short: ""

abstract: "Many e-commerce platforms, such as AliExpress, run major promotion campaigns regularly. Before such a promotion, it is important to predict potential best sellers and their respective sales volumes, so that the platform can arrange their supply chains and logistics accordingly. For items with a sufficiently long sales history, accurate sales forecast can be achieved through the traditional statistical forecasting techniques. To accurately predict the sales volume of a new item, however, is rather challenging with existing methods: time series models tend to overfit due to the very limited historical sales records of the new item, whereas models that do not utilize historical information often fail to make accurate predictions, due to the lack of strong indicators of sales volume among the item’s basic attributes. This paper presents the solution deployed at Alibaba in 2019, which had been used in production to prepare for its annual “Double 11” promotion event whose total sales amount exceeded 38 billion US dollars in a single day. The main idea of the proposed solution is to predict the sales volume of each new item through its connections with older products with sufficiently long sales history. In other words, our solution takes into account the cross-selling effects between different products, which has been largely neglected in previous methods. Specifically, the proposed solution first constructs an item graph, in which each new item is connected to relevant older items. Then, a novel multi-task graph convolutional neural network (GCN) is trained by a multi-objective optimization based gradient surgery technique to predict the expected sales volumes of new items. The designs of both the item graph and the GCN exploit the fact that we only need to perform accurate sales forecasts for potential best-selling items in a major promotion, which helps reduce computational overhead. Extensive experiments on both proprietary AliExpress data and a public dataset demonstrate that the proposed solution achieves consistent performance gains compared to existing methods for sales forecast."

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
