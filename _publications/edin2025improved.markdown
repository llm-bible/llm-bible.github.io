---
layout: publication
title: 'GIM: Improved Interpretability For Large Language Models'
authors: Joakim Edin, Róbert Csordás, Tuukka Ruotsalo, Zhengxuan Wu, Maria Maistro, Jing Huang, Lars Maaløe
conference: "Arxiv"
year: 2025
bibkey: edin2025improved
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17630"}
  - {name: "Code", url: "https://github.com/JoakimEdin/gim"}
tags: ['Responsible AI', 'Model Architecture', 'TACL', 'Transformer', 'Has Code', 'ACL', 'Interpretability and Explainability', 'Attention Mechanism']
---
Ensuring faithful interpretability in large language models is imperative for trustworthy and reliable AI. A key obstacle is self-repair, a phenomenon where networks compensate for reduced signal in one component by amplifying others, masking the true importance of the ablated component. While prior work attributes self-repair to layer normalization and back-up components that compensate for ablated components, we identify a novel form occurring within the attention mechanism, where softmax redistribution conceals the influence of important attention scores. This leads traditional ablation and gradient-based methods to underestimate the significance of all components contributing to these attention scores. We introduce Gradient Interaction Modifications (GIM), a technique that accounts for self-repair during backpropagation. Extensive experiments across multiple large language models (Gemma 2B/9B, LLAMA 1B/3B/8B, Qwen 1.5B/3B) and diverse tasks demonstrate that GIM significantly improves faithfulness over existing circuit identification and feature attribution methods. Our work is a significant step toward better understanding the inner mechanisms of LLMs, which is crucial for improving them and ensuring their safety. Our code is available at https://github.com/JoakimEdin/gim.
