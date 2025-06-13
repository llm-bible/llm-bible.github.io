---
layout: publication
title: 'Leveraging Retrieval-augmented Tags For Large Vision-language Understanding In Complex Scenes'
authors: Antonio Carlos Rivera, Anthony Moore, Steven Robinson
conference: "Arxiv"
year: 2024
bibkey: rivera2024leveraging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.11396'}
tags: ['RAG', 'Tools', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Object-aware reasoning in vision-language tasks poses significant challenges
for current models, particularly in handling unseen objects, reducing
hallucinations, and capturing fine-grained relationships in complex visual
scenes. To address these limitations, we propose the Vision-Aware
Retrieval-Augmented Prompting (VRAP) framework, a generative approach that
enhances Large Vision-Language Models (LVLMs) by integrating
retrieval-augmented object tags into their prompts. VRAP introduces a novel
pipeline where structured tags, including objects, attributes, and
relationships, are extracted using pretrained visual encoders and scene graph
parsers. These tags are enriched with external knowledge and incorporated into
the LLM's input, enabling detailed and accurate reasoning. We evaluate VRAP
across multiple vision-language benchmarks, including VQAv2, GQA, VizWiz, and
COCO, achieving state-of-the-art performance in fine-grained reasoning and
multimodal understanding. Additionally, our ablation studies highlight the
importance of retrieval-augmented tags and contrastive learning, while human
evaluations confirm VRAP's ability to generate accurate, detailed, and
contextually relevant responses. Notably, VRAP achieves a 40% reduction in
inference latency by eliminating runtime retrieval. These results demonstrate
that VRAP is a robust and efficient framework for advancing object-aware
multimodal reasoning.
