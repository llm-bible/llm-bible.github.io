---
layout: publication
title: "Visual Prompt Tuning"
authors: Jia Menglin, Tang Luming, Chen Bor-chun, Cardie Claire, Belongie Serge, Hariharan Bharath, Lim Ser-nam
conference: "Arxiv"
year: 2022
bibkey: jia2022visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.12119"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
The current modus operandi in adapting pre-trained models involves updating all the backbone parameters ie full fine-tuning. This paper introduces Visual Prompt Tuning (VPT) as an efficient and effective alternative to full fine-tuning for large-scale Transformer models in vision. Taking inspiration from recent advances in efficiently tuning large language models VPT introduces only a small amount (less than 137; of model parameters) of trainable parameters in the input space while keeping the model backbone frozen. Via extensive experiments on a wide variety of downstream recognition tasks we show that VPT achieves significant performance gains compared to other parameter efficient tuning protocols. Most importantly VPT even outperforms full fine-tuning in many cases across model capacities and training data scales while reducing per-task storage cost.
