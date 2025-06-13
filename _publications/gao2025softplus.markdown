---
layout: publication
title: 'Softplus Attention With Re-weighting Boosts Length Extrapolation In Large Language Models'
authors: Bo Gao, Michael W. Spratling
conference: "Arxiv"
year: 2025
bibkey: gao2025softplus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13428"}
tags: ['Transformer', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism']
---
Large language models have achieved remarkable success in recent years, primarily due to the implementation of self-attention mechanisms. However, traditional Softmax attention suffers from numerical instability and reduced performance as the length of inference tokens increases. This paper addresses these issues by decomposing the Softmax operation into a non-linear transformation and the \\(l_1\\)-norm. We identify the latter as essential for maintaining model performance. By replacing the non-linear transformation with the Softplus activation function and introducing a dynamic scale factor for different token lengths based on invariance entropy, we create a novel attention mechanism with performance better than conventional Softmax attention across various inference lengths. To further improve the length extrapolation ability of the proposed attention mechanism, we introduce a novel re-weighting mechanism that amplifies significant attention weights while diminishing weaker ones, enabling the model to concentrate more effectively on relevant tokens. When combined with our proposed attention mechanism, this approach maintains nearly constant validation loss even at 16\\(\times\\) the training token length, ensures numerical stability, and achieves superior results on downstream benchmarks.
