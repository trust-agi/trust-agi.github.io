---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Divide and Denoise: Empowering Simple Models for Robust Semi-Supervised Node Classification against Label Noise"
authors: [Kaize Ding, Xiaoxiao Ma, Yixin Liu, Shirui Pan]
date: 2024-08-25T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-05-15T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), Aug 25, 2024 - Aug 29, 2024, Barcelona, Spain (CORE A*)"
publication_short: ""

abstract: "Graph neural networks (GNNs) based on message passing have achieved remarkable performance in graph machine learning. By combining it with the power of pseudo labeling, one can further push forward the performance on the task of semi-supervised node classification. However, most existing works assume that the training node labels are purely noise-free, while this strong assumption usually does not hold in practice. GNNs will overfit the noisy training labels and the adverse effects of mislabeled nodes can be exaggerated by being propagated to the remaining nodes through the graph structure, exacerbating the model failure. Worse still, the noisy pseudo labels could also largely undermine the model's reliability without special treatment. In this paper, we revisit the role of (1) message passing and (2) pseudo labels in the studied problem and try to address two denoising subproblems from the model architecture and algorithm perspective, respectively. Specifically, we first develop a label-noise robust GNN that discards the coupled message-passing scheme. Despite its simple architecture, this learning backbone prevents overfitting to noisy labels and also inherently avoids the noise propagation issue. Moreover, we propose a novel reliable graph pseudo labeling algorithm that can effectively leverage the knowledge of unlabeled nodes while mitigating the adverse effects of noisy pseudo labels. Based on those novel designs, we can attain exceptional effectiveness and efficiency in solving the studied problem. We conduct extensive experiments on benchmark datasets for semi-supervised node classification with different levels of label noise and show new state-of-the-art performance."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural network]
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
