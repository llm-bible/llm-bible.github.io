---
layout: publication
title: Learning To Decompose Visual Features With Latent Textual Prompts
authors: Wang Feng, Li Manling, Lin Xudong, Lv Hairong, Schwing Alexander G., Ji Heng
conference: "Arxiv"
year: 2022
bibkey: wang2022learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.04287"}
tags: ['Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Security', 'Training Techniques']
---
Recent advances in pre45;training vision45;language models like CLIP have shown great potential in learning transferable visual representations. Nonetheless for downstream inference CLIP45;like models suffer from either 1) degraded accuracy and robustness in the case of inaccurate text descriptions during retrieval45;based inference (the challenge for zero45;shot protocol); or 2) breaking the well45;established vision45;language alignment (the challenge for linear probing). To address them we propose Decomposed Feature Prompting (DeFo). DeFo leverages a flexible number of learnable embeddings as textual input while maintaining the vision45;language dual45;model architecture which enables the model to learn decomposed visual features with the help of feature45;level textual prompts. We further use an additional linear layer to perform classification allowing a scalable size of language inputs. Our empirical study shows DeFos significance in improving the vision45;language models. For example DeFo obtains 73.237; test accuracy on ImageNet with a ResNet45;50 backbone without tuning any pretrained weights of both the vision and language encoder outperforming zero45;shot CLIP by a large margin of 15.037; and outperforming state45;of45;the45;art vision45;language prompt tuning method by 7.637;.
