---
layout: publication
title: 'Efficient GPT Model Pre-training Using Tensor Train Matrix Representation'
authors: Chekalina Viktoriia, Novikov Georgii, Gusak Julia, Oseledets Ivan, Panchenko Alexander
conference: "Arxiv"
year: 2023
bibkey: chekalina2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.02697"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
"Large-scale transformer models have shown remarkable performance in language modelling tasks. However, such models feature billions of parameters, leading to difficulties in their deployment and prohibitive training costs from scratch. To reduce the number of the parameters in the GPT-2 architecture, we replace the matrices of fully-connected layers with the corresponding Tensor Train Matrix~(TTM) structure. Finally, we customize forward and backward operations through the TTM-based layer for simplicity and the stableness of further training. &#37; The resulting GPT-2-based model stores up to 40&#37; fewer parameters, showing the perplexity comparable to the original model. On the downstream tasks, including language understanding and text summarization, the model performs similarly to the original GPT-2 model. The proposed tensorized layers could be used to efficiently pre-training other Transformer models."
