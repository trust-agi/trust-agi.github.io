---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Online GNN Evaluation Under Test-time Graph Distribution Shifts"
authors: [Xin Zheng, Dongjin Song, Qingsong Wen, Bo Du, Shirui Pan]
date: 2024-05-10T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-01-10T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Learning Representations (ICLR), May 7-11, 2024, Vienna, Austria (CORE A*)"
publication_short: ""

abstract: "Evaluating the performance of a well-trained GNN model on real-world graphs is a pivotal step for reliable GNN online deployment and serving. Due to a lack of test node labels and unknown potential training-test graph data distribution shifts, conventional model evaluation encounters limitations in calculating performance metrics (e.g., test error) and measuring graph data-level discrepancies, particularly when the training graph used for developing GNNs remains unobserved during test time. In this paper, we study a new research problem, online GNN evaluation, which aims to provide valuable insights into the well-trained GNNs's ability to effectively generalize to real-world unlabeled graphs under the test-time graph distribution shifts. Concretely, we develop an effective learning behavior discrepancy score, dubbed LeBeD, to estimate the test-time generalization errors of well-trained GNN models. Through a novel GNN re-training strategy with a parameter-free optimality criterion, the proposed LeBeD comprehensively integrates learning behavior discrepancies from both node prediction and structure reconstruction perspectives. This enables the effective evaluation of the well-trained GNNs' ability to capture test node semantics and structural representations, making it an expressive metric for estimating the generalization error in online GNN evaluation. Extensive experiments on real-world test graphs under diverse graph distribution shifts could verify the effectiveness of the proposed method, revealing its strong correlation with ground-truth test errors on various well-trained GNN models."

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
