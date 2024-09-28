---
layout: publication
title: PMoE Progressive Mixture of Experts with Asymmetric Transformer for Continual Learning
authors: Jung Min Jae, Kim Joohee
conference: "Arxiv"
year: 2024
bibkey: jung2024pmoe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21571"}
tags: ['ARXIV', 'LLM', 'Model Architecture', 'Transformer']
---
Large Language Models (LLMs) encounter significant challenges in continual learning due to catastrophic forgetting where new information overwrites previously acquired knowledge. This limitation leads to substantial environmental and economic waste. In this study we introduce the PMoE Progressive Mixture of Experts with Asymmetric Transformer which aims to minimize forgetting by utilizing an asymmetric design with shallow layers dedicated to general knowledge and deep layers for new knowledge. PMoE incorporates progressively added experts in deep layers and a router that allocates new knowledge to the appropriate experts efficiently. The router positioned adjacent to the deep layers utilizes deep features aggregating consolidated information. This enables the router to perform efficiently allocating new knowledge to the appropriate experts which progressively increase in the deep layers. Extensive experiments on TRACE datasets and general language understanding datasets demonstrate that the proposed PMoE outperforms previous state-of-the-art approaches.
