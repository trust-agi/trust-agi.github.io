---
title: "Differentiable Neural Architecture Search in Equivalent Space with Exploration Enhancement"
date: 2020-09-25
publishDate: 2020-09-25T12:19:12.824998Z
authors: ["Miao Zhang", "Huiqi Li", "Shirui Pan", "Xiaojun Chang", "Zongyuan Ge", "Steven Su"]
publication_types: ["1"]
abstract: "Recent works on One-Shot Neural Architecture Search (NAS) mostly adopt a bilevel optimization scheme to alternatively optimize the supernet weights and architecture parameters after relaxing the discrete search space into a differentiable space. However, the non-negligible incongruence in their relaxation methods is hard to guarantee the differentiable optimization in the continuous space is equivalent to the optimization in the discrete space. Differently, this paper utilizes a variational graph autoencoder to injectively transform the discrete architecture space into an equivalently continuous latent space, to resolve the incongruence. A probabilistic exploration enhancement method is accordingly devised to encourage intelligent exploration during the architecture search in the latent space, to avoid local optimal in architecture search. As the catastrophic forgetting in differentiable One-Shot NAS deteriorates supernet predictive ability and makes the bilevel optimization inefficient, this paper further proposes an architecture complementation method to relieve this deficiency. We analyze the effectiveness of the proposed method, and a series of experiments have been conducted to compare the proposed method with state-of-the-art One-Shot NAS methods."
featured: false
publication: "*Thirty-fourth Conference on Neural Information Processing Systems, NeurIPS-20*"
tags: ["Neural Architecture Search", "Graph Neural Networks"]
---
