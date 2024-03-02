---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Towards Spatio-Temporal Aware Traffic Time Series Forecasting"
authors: [Razvan Cirstea, Bin Yang, Chenjuan Guo, Tung Kieu, Shirui Pan]
date: 2022-06-09T09:36:17+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-03-23T09:36:17+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Data Engineering (ICDE-22)"
publication_short: ""

abstract: "Traffic time series forecasting is challenging due to complex spatio-temporal dynamics—time series from different locations often have distinct patterns; and for the same time series, patterns may vary across time, where, for example, there exist certain periods across a day showing stronger temporal correlations. Although recent forecasting models, in particular deep learning based models, show promising results, they suffer from being spatio-temporal agnostic. Such spatio-temporal agnostic models employ a shared parameter space irrespective of the time series locations and the time periods and they assume that the temporal patterns are similar across locations and does not evolve across time, which may not always hold,thus leading to sub-optimal results. In this work, we propose a framework that aims at turning spatio-temporal agnostic models to spatio-temporal aware models. To do so, we encode time series from different locations into stochastic variables, from which we generate location-specific and time-varying model parameters to better capture the spatio-temporal dynamics. We show howto integrate the framework with canonical attentions to enable spatio-temporal aware attentions. Next, to compensate for the additional overhead introduced by the spatio-temporal aware model parameter generation process, we propose a novel window attention scheme, which helps reduce the complexity from quadratic to linear, making spatio-temporal aware attentions also have competitive efficiency. We show strong empirical evidence on four traffic time series datasets, where the proposed spatio-temporal aware attentions outperform state-of-the-art methods in term of accuracy and efficiency"

# Summary. An optional shortened abstract.
summary: ""

tags: [time series forecasting]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2203.15737.pdf
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
