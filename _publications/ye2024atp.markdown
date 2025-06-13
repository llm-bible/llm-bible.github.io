---
layout: publication
title: 'Atp-llava: Adaptive Token Pruning For Large Vision Language Models'
authors: Xubing Ye, Yukang Gan, Yixiao Ge, Xiao-ping Zhang, Yansong Tang
conference: "Arxiv"
year: 2024
bibkey: ye2024atp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.00447"}
  - {name: "Code", url: "https://yxxxb.github.io/ATP-LLaVA-page/"}
tags: ['Efficiency and Optimization', 'RAG', 'Pruning', 'Has Code', 'Prompting']
---
Large Vision Language Models (LVLMs) have achieved significant success across
multi-modal tasks. However, the computational cost of processing long visual
tokens can be prohibitively expensive on resource-limited devices. Previous
methods have identified redundancy in visual tokens within the Large Language
Model (LLM) decoder layers and have mitigated this by pruning tokens using a
pre-defined or fixed ratio, thereby reducing computational overhead.
Nonetheless, we observe that the impact of pruning ratio varies across
different LLM layers and instances (image-prompt pairs). Therefore, it is
essential to develop a layer-wise and instance-wise vision token pruning
strategy to balance computational cost and model performance effectively. We
propose ATP-LLaVA, a novel approach that adaptively determines
instance-specific token pruning ratios for each LLM layer. Specifically, we
introduce an Adaptive Token Pruning (ATP) module, which computes the importance
score and pruning threshold based on input instance adaptively. The ATP module
can be seamlessly integrated between any two LLM layers with negligible
computational overhead. Additionally, we develop a Spatial Augmented Pruning
(SAP) strategy that prunes visual tokens with both token redundancy and spatial
modeling perspectives. Our approach reduces the average token count by 75%
while maintaining performance, with only a minimal 1.9% degradation across
seven widely used benchmarks. The project page can be accessed via
https://yxxxb.github.io/ATP-LLaVA-page/.
