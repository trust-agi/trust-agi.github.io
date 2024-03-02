---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Multivariate Time Series Forecasting with Dynamic Graph Neural ODEs"
authors: [Ming Jin, Yu Zheng, Yuan-Fang Li, Siheng Chen, Bin Yang, Shirui Pan]
date: 2022-11-25T09:36:17+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-10-29T09:36:17+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Knowledge and Data Engineering (TKDE)"
publication_short: ""

abstract: "Multivariate time series forecasting has long received significant attention in real-world applications, such as energy consumption and traffic prediction. While recent methods demonstrate good forecasting abilities, they suffer from three fundamental limitations. (i) Discrete neural architectures: Interlacing individually parameterized spatial and temporal blocks to encode rich underlying patterns leads to discontinuous latent state trajectories and higher forecasting numerical errors. (ii) High complexity: Discrete approaches complicate models with dedicated designs and redundant parameters, leading to higher computational and memory overheads. (iii) Reliance on graph priors: Relying on predefined static graph structures limits their effectiveness and practicability in real-world applications. In this paper, we address all the above limitations by proposing a continuous model to forecast Multivariate Time series with dynamic Graph neural Ordinary Differential Equations (MTGODE). Specifically, we first abstract multivariate time series into dynamic graphs with time-evolving node features and unknown graph structures. Then, we design and solve a neural ODE to complement missing graph topologies and unify both spatial and temporal message passing, allowing deeper graph propagation and fine-grained temporal information aggregation to characterize stable and precise latent spatial-temporal dynamics. Our experiments demonstrate the superiorities of MTGODE from various perspectives on five time series benchmark datasets."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks, time series]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2202.08408.pdf
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
