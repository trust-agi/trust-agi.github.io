---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Reinforced, Incremental and Cross-lingual Event Detection From Social Messages"
authors: [Hao Peng, Ruitong Zhang, Shaoning Li, Yuwei Cao, Shirui Pan, Philip S. Yu]
date: 2022-11-25T09:36:17+11:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-01-18T09:36:17+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)"
publication_short: ""

abstract: "Detecting hot social events (e.g. political scandal, momentous meetings, natural hazards, etc.) from social messages iscrucial as it highlights significant happenings to help people understand the real world. On account of the streaming nature of socialmessages, incremental social event detection models in acquiring, preserving, and updating messages over time have attracted greatattention. However, the challenge is that the existing event detection methods towards streaming social messages are generallyconfronted with ambiguous events features, dispersive text contents, and multiple languages, and hence result in low accuracy andgeneralization ability. In this paper, we present a novel reinForced,incremental and cross-lingual socialEventdetection architecture,namelyFinEvent, from streaming social messages. Concretely, we first model social messages into heterogeneous graphs integratingboth rich meta-semantics and diverse meta-relations, and convert them to weighted multi-relational message graphs. Secondly, wepropose a new reinforced weighted multi-relational graph neural network framework by using a Multi-agent Reinforcement Learningalgorithm to select optimal aggregation thresholds across different relations/edges to learn social message embeddings. To solve thelong-tail problem in social event detection, a balanced sampling strategy guided Contrastive Learning mechanism is designed forincremental social message representation learning. Thirdly, a new Deep Reinforcement Learning guided density-based spatialclustering model is designed to select the optimal minimum number of samples required to form a cluster and optimal minimumdistance between two clusters in social event detection tasks. Finally, we implement incremental social message representationlearning based on knowledge preservation on the graph neural network and achieve the transferring cross-lingual social eventdetection. We conduct extensive experiments to evaluate theFinEventon Twitter streams, demonstrating a significant and consistentimprovement in model quality with 14%-118%, 8%-170%, and 2%-21% increases in performance on offline, online, and cross-lingualsocial event detection tasks."

# Summary. An optional shortened abstract.
summary: ""

tags: [graph neural networks, social event detection]
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
