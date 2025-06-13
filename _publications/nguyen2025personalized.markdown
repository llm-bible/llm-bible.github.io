---
layout: publication
title: 'Yochameleon: Personalized Vision And Language Generation'
authors: Thao Nguyen, Krishna Kumar Singh, Jing Shi, Trung Bui, Yong Jae Lee, Yuheng Li
conference: "Arxiv"
year: 2025
bibkey: nguyen2025personalized
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.20998'}
tags: ['Language Modeling', 'Few-Shot', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'GPT', 'Prompting', 'Applications', 'Multimodal Models']
---
Large Multimodal Models (e.g., GPT-4, Gemini, Chameleon) have evolved into
powerful tools with millions of users. However, they remain generic models and
lack personalized knowledge of specific user concepts. Previous work has
explored personalization for text generation, yet it remains unclear how these
methods can be adapted to new modalities, such as image generation. In this
paper, we introduce Yo'Chameleon, the first attempt to study personalization
for large multimodal models. Given 3-5 images of a particular concept,
Yo'Chameleon leverages soft-prompt tuning to embed subject-specific information
to (i) answer questions about the subject and (ii) recreate pixel-level details
to produce images of the subject in new contexts. Yo'Chameleon is trained with
(i) a self-prompting optimization mechanism to balance performance across
multiple modalities, and (ii) a ``soft-positive" image generation approach to
enhance image quality in a few-shot setting.
