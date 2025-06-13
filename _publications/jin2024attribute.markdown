---
layout: publication
title: 'ARMADA: Attribute-based Multimodal Data Augmentation'
authors: Xiaomeng Jin, Jeonghwan Kim, Yu Zhou, Kuan-hao Huang, Te-lin Wu, Nanyun Peng, Heng Ji
conference: "Arxiv"
year: 2024
bibkey: jin2024attribute
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10086"}
tags: ['Masked Language Model', 'Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability']
---
In Multimodal Language Models (MLMs), the cost of manually annotating
high-quality image-text pair data for fine-tuning and alignment is extremely
high. While existing multimodal data augmentation frameworks propose ways to
augment image-text pairs, they either suffer from semantic inconsistency
between texts and images, or generate unrealistic images, causing knowledge gap
with real world examples. To address these issues, we propose Attribute-based
Multimodal Data Augmentation (ARMADA), a novel multimodal data augmentation
method via knowledge-guided manipulation of visual attributes of the mentioned
entities. Specifically, we extract entities and their visual attributes from
the original text data, then search for alternative values for the visual
attributes under the guidance of knowledge bases (KBs) and large language
models (LLMs). We then utilize an image-editing model to edit the images with
the extracted attributes. ARMADA is a novel multimodal data generation
framework that: (i) extracts knowledge-grounded attributes from symbolic KBs
for semantically consistent yet distinctive image-text pair generation, (ii)
generates visually similar images of disparate categories using neighboring
entities in the KB hierarchy, and (iii) uses the commonsense knowledge of LLMs
to modulate auxiliary visual attributes such as backgrounds for more robust
representation of original entities. Our empirical results over four downstream
tasks demonstrate the efficacy of our framework to produce high-quality data
and enhance the model performance. This also highlights the need to leverage
external knowledge proxies for enhanced interpretability and real-world
grounding.
