---
layout: publication
title: 'Med-moe: Mixture Of Domain-specific Experts For Lightweight Medical Vision-language Models'
authors: Songtao Jiang, Tuo Zheng, Yan Zhang, Yeying Jin, Li Yuan, Zuozhu Liu
conference: "Arxiv"
year: 2024
bibkey: jiang2024med
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10237"}
tags: ['Training Techniques', 'Multimodal Models', 'Applications', 'Tools']
---
Recent advancements in general-purpose or domain-specific multimodal large
language models (LLMs) have witnessed remarkable progress for medical
decision-making. However, they are designated for specific classification or
generative tasks, and require model training or finetuning on large-scale
datasets with sizeable parameters and tremendous computing, hindering their
clinical utility across diverse resource-constrained scenarios in practice. In
this paper, we propose a novel and lightweight framework Med-MoE
(Mixture-of-Experts) that tackles both discriminative and generative multimodal
medical tasks. The learning of Med-MoE consists of three steps: multimodal
medical alignment, instruction tuning and routing, and domain-specific MoE
tuning. After aligning multimodal medical images with LLM tokens, we then
enable the model for different multimodal medical tasks with instruction
tuning, together with a trainable router tailored for expert selection across
input modalities. Finally, the model is tuned by integrating the router with
multiple domain-specific experts, which are selectively activated and further
empowered by meta expert. Comprehensive experiments on both open- and close-end
medical question answering (Med-VQA) and image classification tasks across
datasets such as VQA-RAD, SLAKE and Path-VQA demonstrate that our model can
achieve performance superior to or on par with state-of-the-art baselines,
while only requiring approximately 30%-50% of activated model parameters.
Extensive analysis and ablations corroborate the effectiveness and practical
utility of our method.
