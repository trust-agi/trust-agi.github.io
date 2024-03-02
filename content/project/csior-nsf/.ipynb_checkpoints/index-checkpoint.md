---
title: Towards Interpretable and Responsible Graph Modeling for Dynamic Systems
summary: CSIRO-NSF Responsible AI Grant
tags:
  - Trustworthy AI
date: '2023-12-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by GPT4
  focal_point: Smart
  preview_only: false
  filename: nsf.jpg  # Uncomment to load an image from `assets/media/` instead.

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: NSF Annoucement
#    url: https://www.nsf.gov/awardsearch/showAward?AWD_ID=2302786&HistoricalAwards=false
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
**Grant:** CSIRO-NSF Responsible AI Grant (2023-2026)

**Description:**
Real-world natural and engineered systems (e.g., food web, power grids, river networks, and ocean current networks) are inherently complicated and are driven by many factors with dependency relationships. Graphs have been commonly used to represent the structure and content of these systems for event prediction and risk estimation. To date, many graph learning methods, such as graph neural networks, have been proposed, but primarily for static graphs. In dynamic systems, the structure and content are simultaneously evolving in response to emerging trends and events, making it difficult to understand and interpret how each part of the graph functions in forming reliable models for predictions. This project strives to build a graph learning and interpretation framework for dynamic systems by combining sensor pattern discovery, node interaction and network functionality analysis, and physics- and knowledge-informed learning. The project will propose new algorithms for modeling and understanding large-scale dynamic systems using graphs, as well as develop a prototype for domain experts to analyze their data, explain what is currently happening in the system, understand the resulting consequences, and provide possible mitigation strategies. The joint effort between the US and Australian teams will help understand/uncover the dynamics of water monitoring systems for different terrain types, inland and coastal water exchange, toxic algal blooms, and resilience of rural and regional communities.

The project includes three main thrusts: (1) sensor signal to feature extraction and understanding; (2) dynamic network node modeling and interpretation; and (3) dynamic network functionality and trustworthiness. The research will study signal snippet pattern (SSP) extraction and interaction analysis to understand how features interact with each other during the emergence of significant events. At the node level, new temporal encoding and spatial-temporal graph neural networks will be used to learn models for node event prediction and anomaly detection for early warning. The study of node interaction will answer why, when, and how two nodes may be interacting with each other. Beyond node level interpretation, the project will target graph functional units, estimate each snapshot graph?s contribution, and locate subgraphs with the highest significance concerning output systems. A perturbation-based post-hoc explainer will provide counterfactual explanations to enhance the explainability and trustworthiness of dynamic graph neural network systems. The research will also investigate combining physics laws and domain knowledge into dynamic graph neural networks to develop a data-efficient, robust, and responsible graph modeling framework.

This is a joint project between U.S. and Australian researchers funded by the Collaboration Opportunities in Responsible and Equitable AI under the U.S. NSF and the Australian Commonwealth Scientific and Industrial Research Organisation (CSIRO).