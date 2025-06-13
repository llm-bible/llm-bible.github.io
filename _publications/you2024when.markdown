---
layout: publication
title: 'When Linear Attention Meets Autoregressive Decoding: Towards More Effective And Efficient Linearized Large Language Models'
authors: Haoran You, Yichao Fu, Zheng Wang, Amir Yazdanbakhsh, Yingyan Celine Lin
conference: "Arxiv"
year: 2024
bibkey: you2024when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07368"}
  - {name: "Code", url: "https://github.com/GATECH-EIC/Linearized-LLM"}
tags: ['Efficiency and Optimization', 'GPT', 'Survey Paper', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Autoregressive Large Language Models (LLMs) have achieved impressive
performance in language tasks but face two significant bottlenecks: (1)
quadratic complexity in the attention module as the number of tokens increases,
and (2) limited efficiency due to the sequential processing nature of
autoregressive LLMs during generation. While linear attention and speculative
decoding offer potential solutions, their applicability and synergistic
potential for enhancing autoregressive LLMs remain uncertain. We conduct the
first comprehensive study on the efficacy of existing linear attention methods
for autoregressive LLMs, integrating them with speculative decoding. We
introduce an augmentation technique for linear attention that ensures
compatibility with speculative decoding, enabling more efficient training and
serving of LLMs. Extensive experiments and ablation studies involving seven
existing linear attention models and five encoder/decoder-based LLMs
consistently validate the effectiveness of our augmented linearized LLMs.
Notably, our approach achieves up to a 6.67 reduction in perplexity on the
LLaMA model and up to a 2\\(\times\\) speedup during generation compared to prior
linear attention methods. Codes and models are available at
https://github.com/GATECH-EIC/Linearized-LLM.
