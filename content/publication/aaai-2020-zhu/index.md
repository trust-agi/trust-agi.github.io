---
title: "GSSNN: Graph Smoothing Splines Neural Networks"
date: 2020-01-07
publishDate: 2020-01-07T12:15:49.436331Z
authors: ["Shichao Zhu", "Lewei Zhou", "Shirui Pan", "Chuan Zhou", "Guiying Yan", "Bin Wang"]
publication_types: ["1"]
abstract: "Graph Neural Networks (GNNs) have achieved state-of-the-art performance in many graph data analysis tasks. However, they still suffer from two limitations for graph represen-tation learning. First, they exploit non-smoothing node fea-tures which may result in suboptimal embedding and degen-erated performance for graph classification. Second, they on-ly exploit neighbor information but ignore global topologicalknowledge. Aiming to overcome these limitations simultane-ously, in this paper, we propose a novel, flexible, and end-to-end framework, Graph Smoothing Splines Neural Networks(GSSNN), for graph classification. By exploiting the smooth-ing  splines,  which  are  widely  used  to  learn  smoothing  fit-ting function in regression, we develop an effective featuresmoothing  and  enhancement  module  Scaled  Smoothing  S-plines  (S3)  to  learn  graph  embedding.  To  integrate  globaltopological information, we design a novel scoring module,which exploits closeness, degree, as well as self-attention val-ues, to select important node features as knots for smoothingsplines. These knots can be potentially used for interpretingclassification results. In extensive experiments on biologicaland social datasets, we demonstrate that our model achievesstate-of-the-arts and GSSNN is superior in learning more ro-bust  graph  representations.  Furthermore,  we  show  that  S3module is easily plugged into existing GNNs to improve theirperformance."
featured: false
publication: "*AAAI Conference on Artificial Intelligence, AAAI-20*"
tags: ["Data Mining", "Relational Learning", "Networks","Graph Neural Networks"]
url_code: "https://github.com/CheriseZhu/GSSNN"
---

