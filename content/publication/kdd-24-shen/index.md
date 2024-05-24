---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Optimizing OOD Detection in Molecular Graphs: A Novel Approach with Diffusion Models"
authors: [Xu Shen, Yili Wang, Kaixiong Zhou, Shirui Pan, Xin Wang]
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

abstract: "The open-world test dataset is often mixed with out-of-distribution (OOD) samples, where the deployed models will struggle to make accurate predictions. Traditional detection methods need to trade off OOD detection and in-distribution (ID) classification performance since they share the same representation learning model. In this work, we propose to detect OOD molecules by adopting an auxiliary diffusion model-based framework, which compares similarities between input molecules and reconstructed graphs. Due to the generative bias towards reconstructing ID training samples, the similarity scores of OOD molecules will be much lower to facilitate detection. Although it is conceptually simple, extending this vanilla framework to practical detection applications is still limited by two significant challenges. First, the popular similarity metrics based on Euclidian distance fail to consider the complex graph structure. Second, the generative model involving iterative denoising steps is time-consuming especially when it runs on the enormous pool of drugs. To address these challenges, our research pioneers an approach of Prototypical Graph Reconstruction for Molecular OOD Detection, dubbed as PGR-MOOD and hinges on three innovations: i) An effective metric to comprehensively quantify the matching degree of input and reconstructed molecules; ii) A creative graph generator to construct prototypical graphs that are in line with ID but away from OOD; iii) An efficient and scalable OOD detector to compare the similarity between test samples and pre-constructed prototypical graphs and omit the generative process on every new molecule. Extensive experiments on ten benchmark datasets and six baselines are conducted to demonstrate our superiority."

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
