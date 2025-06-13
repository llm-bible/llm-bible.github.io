---
layout: publication
title: 'Does Representation Matter? Exploring Intermediate Layers In Large Language Models'
authors: Oscar Skean, Md Rifat Arefin, Yann Lecun, Ravid Shwartz-ziv
conference: "Arxiv"
year: 2024
bibkey: skean2024does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.09563"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Interpretability and Explainability', 'Prompting', 'Applications']
---
Understanding what defines a good representation in large language models
(LLMs) is fundamental to both theoretical understanding and practical
applications. In this paper, we investigate the quality of intermediate
representations in various LLM architectures, including Transformers and State
Space Models (SSMs). We find that intermediate layers often yield more
informative representations for downstream tasks than the final layers. To
measure the representation quality, we adapt and apply a suite of metrics -
such as prompt entropy, curvature, and augmentation-invariance - originally
proposed in other contexts. Our empirical study reveals significant
architectural differences, how representations evolve throughout training, and
how factors like input randomness and prompt length affect each layer. Notably,
we observe a bimodal pattern in the entropy of some intermediate layers and
consider potential explanations tied to training data. Overall, our results
illuminate the internal mechanics of LLMs and guide strategies for
architectural optimization and training.
