---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Demystifying Uneven Vulnerability of Link Stealing Attacks against Graph Neural Networks"
authors: [He Zhang, Bang Wu, Shuo Wang, Xiangwen Yang, Minhui Xue, Shirui Pan, Xingliang Yuan]
date: 2023-07-23T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-04-24T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2023 International Conference on Machine Learning (ICML), Honolulu, Hawaii, USA, July 23 - July 29, 2023 (CORE A*)"
publication_short: ""

abstract: "While graph neural networks (GNNs) dominate the state-of-the-art for exploring graphs in real-world applications, they have been shown to be vulnerable to a growing number of privacy attacks. For instance, link stealing is a well-known membership inference attack (MIA) on edges that infers the presence of an edge in a GNN's training graph. Recent studies on independent and identically distributed data (e.g., images) have empirically demonstrated that individuals from different groups suffer from different levels of privacy risks to MIAs, i.e., uneven vulnerability. However, theoretical evidence of such uneven vulnerability is missing. In this paper, we first present theoretical evidence of the uneven vulnerability of GNNs to link stealing attacks, which lays the foundation for demystifying such uneven risks among different groups of edges. We further demonstrate a group-based attack paradigm to expose the practical privacy harm to GNN users derived from the uneven vulnerability of edges. Finally, we empirically validate the existence of obvious uneven vulnerability on nine real-world datasets (e.g., about 25% AUC difference between different groups in the Credit graph). Compared with existing methods, the outperformance of our group-based attack paradigm confirms that customising different strategies for different groups results in more effective privacy attacks."

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

url_pdf: https://proceedings.mlr.press/v202/zhang23aq/zhang23aq.pdf
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
