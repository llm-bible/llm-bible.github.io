---
layout: publication
title: 'Lightlm: A Lightweight Deep And Narrow Language Model For Generative Recommendation'
authors: Mei Kai, Zhang Yongfeng
conference: "Arxiv"
year: 2023
bibkey: mei2023lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17488"}
  - {name: "Code", url: "https://github.com/dongyuanjushi/LightLM"}
tags: ['Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
This paper presents LightLM, a lightweight Transformer-based language model for generative recommendation. While Transformer-based generative modeling has gained importance in various AI sub-fields such as NLP and vision, generative recommendation is still in its infancy due to its unique demand on personalized generative modeling. Existing works on generative recommendation often use NLP-oriented Transformer architectures such as T5, GPT, LLaMA and M6, which are heavy-weight and are not specifically designed for recommendation tasks. LightLM tackles the issue by introducing a light-weight deep and narrow Transformer architecture, which is specifically tailored for direct generation of recommendation items. This structure is especially apt for straightforward generative recommendation and stems from the observation that language model does not have to be too wide for this task, as the input predominantly consists of short tokens that are well-suited for the model's capacity. We also show that our devised user and item ID indexing methods, i.e., Spectral Collaborative Indexing (SCI) and Graph Collaborative Indexing (GCI), enables the deep and narrow Transformer architecture to outperform large-scale language models for recommendation. Besides, to address the hallucination problem of generating items as output, we propose the constrained generation process for generative recommenders. Experiments on real-world datasets show that LightLM outperforms various competitive baselines in terms of both recommendation accuracy and efficiency. The code can be found at https://github.com/dongyuanjushi/LightLM.
