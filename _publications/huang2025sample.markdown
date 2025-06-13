---
layout: publication
title: 'Sample Complexity And Representation Ability Of Test-time Scaling Paradigms'
authors: Baihe Huang, Shanda Li, Tianhao Wu, Yiming Yang, Ameet Talwalkar, Kannan Ramchandran, Michael I. Jordan, Jiantao Jiao
conference: "Arxiv"
year: 2025
bibkey: huang2025sample
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.05295'}
tags: ['Efficiency and Optimization', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
Test-time scaling paradigms have significantly advanced the capabilities of large language models (LLMs) on complex tasks. Despite their empirical success, theoretical understanding of the sample efficiency of various test-time strategies -- such as self-consistency, best-of-\\(n\\), and self-correction -- remains limited. In this work, we first establish a separation result between two repeated sampling strategies: self-consistency requires \\(\Theta(1/\Delta^2)\\) samples to produce the correct answer, while best-of-\\(n\\) only needs \\(\Theta(1/\Delta)\\), where \\(\Delta < 1\\) denotes the probability gap between the correct and second most likely answers. Next, we present an expressiveness result for the self-correction approach with verifier feedback: it enables Transformers to simulate online learning over a pool of experts at test time. Therefore, a single Transformer architecture can provably solve multiple tasks without prior knowledge of the specific task associated with a user query, extending the representation theory of Transformers from single-task to multi-task settings. Finally, we empirically validate our theoretical results, demonstrating the practical effectiveness of self-correction methods.
