---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Probabilistic Graphical Model Based on Neural-symbolic Reasoning for Visual Relationship Detection"
authors: [Dongran Yu, Bo Yang, Qianhao Wei, Anchen Li, Shirui Pan]
date: 2022-06-29T09:36:17+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-03-01T09:36:17+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR-22)"
publication_short: ""

abstract: "This paper aims to leverage symbolic knowledge to improve the performance and interpretability of the Visual Relationship Detection (VRD) models. Existing VRD methods based on deep learning suffer from the problems of poor performance on insufficient labeled examples and lack of interpretability. To overcome the aforementioned weaknesses, we integrate symbolic knowledge into deep learning models and propose a bi-level probabilistic graphical reasoning framework called BPGR. Specifically, in the high-level structure, we take the objects and relationships detected by the VRD model as hidden variables (reasoning results); In the low-level structure of BPGR, we use Markov Logic Networks (MLNs) to project First-Order Logic (FOL) as observed variables (symbolic knowledge) to correct error reasoning results. We adopt a variational EM algorithm for optimization. Experiments results show that our BPGR improves the performance of the VRD models. In particular, BPGR can also provide easy-to-understand insights for reasoning results to show interpretability."

# Summary. An optional shortened abstract.
summary: ""

tags: [visual reasoning]
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
