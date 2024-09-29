---
layout: publication
title: Efficient GPT Model Pre45;training Using Tensor Train Matrix Representation
authors: Chekalina Viktoriia, Novikov Georgii, Gusak Julia, Oseledets Ivan, Panchenko Alexander
conference: "Arxiv"
year: 2023
bibkey: chekalina2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.02697"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large45;scale transformer models have shown remarkable performance in language modelling tasks. However such models feature billions of parameters leading to difficulties in their deployment and prohibitive training costs from scratch. To reduce the number of the parameters in the GPT45;2 architecture we replace the matrices of fully45;connected layers with the corresponding Tensor Train Matrix~(TTM) structure. Finally we customize forward and backward operations through the TTM45;based layer for simplicity and the stableness of further training. 37; The resulting GPT45;245;based model stores up to 4037; fewer parameters showing the perplexity comparable to the original model. On the downstream tasks including language understanding and text summarization the model performs similarly to the original GPT45;2 model. The proposed tensorized layers could be used to efficiently pre45;training other Transformer models.
