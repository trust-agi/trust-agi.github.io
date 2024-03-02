---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Triformer: Triangular, Variable-Specific Attentions for Long Sequence Multivariate Time Series Forecasting"
authors: [Razvan-Gabriel Cirstea, Chenjuan Guo, Bin Yang, Tung Kieu, Xuanyi Dong, Shirui Pan]
date: 2022-07-23T19:47:36+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-04-20T19:47:36+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "31st International Joint Conference on Artificial Intelligence (IJCAI-22), July 23-29, 2022 Messe Wien, Vienna, Austria"
publication_short: ""

abstract: "A variety of real-world applications rely on far future information to make decisions, thus calling for efficient and accurate long sequence multivariate time series forecasting. While recent attention-based forecasting models show strong abilities in capturing long-term dependencies, they still suffer from two key limitations. First, canonical self attention has a quadratic complexity w.r.t. the input time series length, thus falling short in efficiency. Second, different variables’ time series often have distinct temporal dynamics, which existing studies fail to capture, as they use the same model parameter space, e.g., projection matrices, for all variables’ time series, thus falling short in accuracy. To ensure high efficiency and accuracy, we propose TRACE, a triangular, variable-specific attention. (i) Linear complexity: we introduce a novel patch attention with linear complexity. When stacking multiple layers of the patch attentions, a triangular structure is proposed such that the layer sizes shrink exponentially, thus maintaining linear complexity. (ii) Variable-specific parameters: we propose a light-weight method to enable distinct sets of model parameters for different variables’ time series to enhance accuracy without compromising efficiency and memory usage. Strong empirical evidence on four data sets from multiple domains justify our design choices and demonstrate that TRACE outperforms state-of-the-art methods in terms of both accuracy and efficiency."

# Summary. An optional shortened abstract.
summary: ""

tags: [multivariate time series forecasting]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2204.13767.pdf
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
