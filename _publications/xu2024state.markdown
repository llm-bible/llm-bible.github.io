---
layout: publication
title: 'State Space Models Are Strong Text Rerankers'
authors: Zhichao Xu, Jinghua Yan, Ashim Gupta, Vivek Srikumar
conference: "Arxiv"
year: 2024
bibkey: xu2024state
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14354"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Pre-Training', 'Applications', 'Attention Mechanism']
---
Transformers dominate NLP and IR; but their inference inefficiencies and
challenges in extrapolating to longer contexts have sparked interest in
alternative model architectures. Among these, state space models (SSMs) like
Mamba offer promising advantages, particularly \\(O(1)\\) time complexity in
inference. Despite their potential, SSMs' effectiveness at text reranking -- a
task requiring fine-grained query-document interaction and long-context
understanding -- remains underexplored. This study benchmarks SSM-based
architectures (specifically, Mamba-1 and Mamba-2) against transformer-based
models across various scales, architectures, and pre-training objectives,
focusing on performance and efficiency in text reranking tasks. We find that
(1) Mamba architectures achieve competitive text ranking performance,
comparable to transformer-based models of similar size; (2) they are less
efficient in training and inference compared to transformers with flash
attention; and (3) Mamba-2 outperforms Mamba-1 in both performance and
efficiency. These results underscore the potential of state space models as a
transformer alternative and highlight areas for improvement in future IR
applications.
