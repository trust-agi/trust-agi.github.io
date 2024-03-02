---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Dual Intent Enhanced Graph Neural Network for Session-based New Item Recommendation"
authors: [Di Jin, Luzhi Wang, Yizhen Zheng, Guojie Song, Fei Jiang, Xiang Li, Wei Lin, Shirui Pan]
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

abstract: "Recommender systems are essential to various fields, e.g., e-commerce, e-learning, and streaming media. At present, session-based recommendation models are normally based on the next item recommendation, which recommend items existing in users' historical sessions. However, recommending items that users have interacted (old items) will reduce the interest of users interacting with new items and leads to an information cocoon. Therefore, it is necessary to recommend items that users have never interacted (new items), namely, session-based new item recommendation problem. This problem is new and challenging since new items have no interaction with users. It is difficult to learn the representation of new items and recommend them to users effectively. Motivated by these challenges, we propose a dual-intent enhanced graph neural network for the session-based new item recommendation. User intent expresses the user preferences of items, which is the core part of the recommender system. To learn the user's intent effectively and determine the range of new items that are likely to be recommended to users, we use the user's historical session to learn the user intent by an attention mechanism and the distribution of historical data, respectively. Since new items have not interacted with the user, inspired by zero-shot learning (ZSL), we infer the new item representation by using their attributes. Finally, by outputting new item probabilities, which contain recommendation scores of the corresponding items, the new items with higher scores are recommended to users. Experiments on two representative real-world datasets show the superiority of our proposed method. The case study from the real-world verifies interpretability benefits brought by the dual-intents and new item reasoning."

# Summary. An optional shortened abstract.
summary: ""

tags: [recommender systems]
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
projects: [Graph Neural Networks]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
