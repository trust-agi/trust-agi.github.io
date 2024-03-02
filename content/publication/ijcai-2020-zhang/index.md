---
title: "One-Shot Neural Architecture Search via Novelty Driven Sampling"
date: 2020-04-20
publishDate: 2020-04-20T12:15:49.436331Z
authors: ["Miao Zhang", "Huiqi Li", "Shirui Pan", "Taoping Liu", "Steven Su"]
publication_types: ["1"]
abstract: "One-Shot Neural architecture search (NAS) has received wide attention due to its computational efficiency. Many One-Shot NAS methods use the validation accuracy based on the supernet as the stepping stone to search the best performing architecture through a bilevel optimization manner, assuming this validation accuracy approximates to the test accuracy after re-training. However, increasing research has found that there is no positive correlation between the above validation accuracy and test accuracy for these One-Shot NAS methods, and this reward based sampling for supernet training also entails the rich-get-richer problem. To handle this deceptive problem, this paper presents a new approach, Efficient Novelty-driven Neural Architecture Search (EN2AS), to sample the most abnormal architecture to train the supernet. Specifically, a single-path supernet is adopted, and only the weights of the single architecture sampled by our novelty search are optimized in each step to reduce the memory demand greatly. Extensive experiments demonstrate the effectiveness and efficiency of our novelty search based architecture sampling method."
featured: false
publication: "*International Joint Conference on Artificial Intelligence, IJCAI-20*"
tags: ["Neural Architecture Search", "Deep Learning", "AutoML"]
---

