---
layout: publication
title: 'Cogsteer: Cognition-inspired Selective Layer Intervention For Efficiently Steering Large Language Models'
authors: Xintong Wang, Jingheng Pan, Liang Ding, Longyue Wang, Longqin Jiang, Xingshan Li, Chris Biemann
conference: "Arxiv"
year: 2024
bibkey: wang2024cognition
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.17714"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability', 'Applications']
---
Large Language Models (LLMs) achieve remarkable performance through pretraining on extensive data. This enables efficient adaptation to diverse downstream tasks. However, the lack of interpretability in their underlying mechanisms limits the ability to effectively steer LLMs for specific applications. In this work, we investigate the intrinsic mechanisms of LLMs from a cognitive perspective using eye movement measures. Specifically, we analyze the layer-wise correlation between human cognitive indicators and LLM representations. Building on these insights, we propose a heuristic approach for selecting the optimal steering layer to modulate LLM semantics. To this end, we introduce an efficient selective layer intervention based on prominent parameter-efficient fine-tuning methods, which conventionally adjust either all layers or only the final layer. Additionally, we present an implicit layer contrastive intervention during inference to steer LLMs away from toxic outputs. Extensive experiments on natural language understanding, reasoning, and generation tasks, conducted on GPT-2, Llama2-7B, and Mistral-7B, demonstrate the effectiveness and efficiency of our approach. As a model-agnostic framework, it enhances the interpretability of LLMs while improving efficiency for safe deployment.
