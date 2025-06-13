---
layout: publication
title: 'WINA: Weight Informed Neuron Activation For Accelerating Large Language Model Inference'
authors: Sihan Chen, Dan Zhao, Jongwoo Ko, Colby Banbury, Huiping Zhuang, Luming Liang, Tianyi Chen
conference: "Arxiv"
year: 2025
bibkey: chen2025weight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19427"}
  - {name: "Code", url: "https://github.com/microsoft/wina"}
tags: ['Tools', 'Efficiency and Optimization', 'RAG', 'Pruning', 'Model Architecture', 'Training Techniques', 'Has Code']
---
The growing computational demands of large language models (LLMs) make efficient inference and activation strategies increasingly critical. While recent approaches, such as Mixture-of-Experts (MoE), leverage selective activation but require specialized training, training-free sparse activation methods offer broader applicability and superior resource efficiency through their plug-and-play design. However, many existing methods rely solely on hidden state magnitudes to determine activation, resulting in high approximation errors and suboptimal inference accuracy. To address these limitations, we propose WINA (Weight Informed Neuron Activation), a novel, simple, and training-free sparse activation framework that jointly considers hidden state magnitudes and the column-wise \\(ℓ₂\\)-norms of weight matrices. We show that this leads to a sparsification strategy that obtains optimal approximation error bounds with theoretical guarantees tighter than existing techniques. Empirically, WINA also outperforms state-of-the-art methods (e.g., TEAL) by up to \\(2.94%\\) in average performance at the same sparsity levels, across a diverse set of LLM architectures and datasets. These results position WINA as a new performance frontier for training-free sparse activation in LLM inference, advancing training-free sparse activation methods and setting a robust baseline for efficient inference. The source code is available at https://github.com/microsoft/wina.
