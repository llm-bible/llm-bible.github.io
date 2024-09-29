---
layout: publication
title: Controlmllm&#58; Training-free Visual Prompt Learning For Multimodal Large Language Models
authors: Wu Mingrui, Cai Xinyue, Ji Jiayi, Li Jiale, Huang Oucheng, Luo Gen, Fei Hao, Sun Xiaoshuai, Ji Rongrong
conference: "Arxiv"
year: 2024
bibkey: wu2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21534"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
In this work we propose a training-free method to inject visual referring into Multimodal Large Language Models (MLLMs) through learnable visual token optimization. We observe the relationship between text prompt tokens and visual tokens in MLLMs where attention layers model the connection between them. Our approach involves adjusting visual tokens from the MLP output during inference controlling which text prompt tokens attend to which visual tokens. We optimize a learnable visual token based on an energy function enhancing the strength of referential regions in the attention map. This enables detailed region description and reasoning without the need for substantial training costs or model retraining. Our method offers a promising direction for integrating referential abilities into MLLMs. Our method support referring with box mask scribble and point. The results demonstrate that our method exhibits controllability and interpretability.
