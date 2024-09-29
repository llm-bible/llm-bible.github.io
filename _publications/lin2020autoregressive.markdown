---
layout: publication
title: Autoregressive Knowledge Distillation through Imitation Learning
authors: Lin Alexander, Wohlwend Jeremy, Chen Howard, Lei Tao
conference: "Arxiv"
year: 2020
bibkey: lin2020autoregressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.07253"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Ethics And Bias', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
The performance of autoregressive models on natural language generation tasks has dramatically improved due to the adoption of deep self-attentive architectures. However these gains have come at the cost of hindering inference speed making state-of-the-art models cumbersome to deploy in real-world time-sensitive settings. We develop a compression technique for autoregressive models that is driven by an imitation learning perspective on knowledge distillation. The algorithm is designed to address the exposure bias problem. On prototypical language generation tasks such as translation and summarization our method consistently outperforms other distillation algorithms such as sequence-level knowledge distillation. Student models trained with our method attain 1.4 to 4.8 BLEU/ROUGE points higher than those trained from scratch while increasing inference speed by up to 14 times in comparison to the teacher model.
