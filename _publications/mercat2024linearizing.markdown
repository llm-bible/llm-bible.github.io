---
layout: publication
title: 'Linearizing Large Language Models'
authors: Mercat Jean, Vasiljevic Igor, Keh Sedrick, Arora Kushal, Dave Achal, Gaidon Adrien, Kollar Thomas
conference: "Arxiv"
year: 2024
bibkey: mercat2024linearizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06640"}
  - {name: "Code", url: "https://github.com/TRI-ML/linear_open_lm"}
tags: ['Attention Mechanism', 'Has Code', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
Linear transformers have emerged as a subquadratic-time alternative to
softmax attention and have garnered significant interest due to their
fixed-size recurrent state that lowers inference cost. However, their original
formulation suffers from poor scaling and underperforms compute-matched
transformers. Recent linear models such as RWKV and Mamba have attempted to
address these shortcomings by proposing novel time-mixing and gating
architectures, but pre-training large language models requires significant data
and compute investments. Thus, the search for subquadratic architectures is
limited by the availability of compute and quality pre-training datasets. As a
cost-effective alternative to pre-training linear transformers, we propose
Scalable UPtraining for Recurrent Attention (SUPRA). We present a method to
uptrain existing large pre-trained transformers into Recurrent Neural Networks
(RNNs) with a modest compute budget. This allows us to leverage the strong
pre-training data and performance of existing transformer LLMs, while requiring
5% of the training cost. We find that our linearization technique leads to
competitive performance on standard benchmarks, but we identify persistent
in-context learning and long-context modeling shortfalls for even the largest
linear models. Our code and models can be found at
https://github.com/TRI-ML/linear_open_lm.
