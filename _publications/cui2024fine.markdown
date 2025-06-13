---
layout: publication
title: 'Fine-grained Verifiers: Preference Modeling As Next-token Prediction In Vision-language Alignment'
authors: Chenhang Cui, An Zhang, Yiyang Zhou, Zhaorun Chen, Gelei Deng, Huaxiu Yao, Tat-seng Chua
conference: "Arxiv"
year: 2024
bibkey: cui2024fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14148'}
tags: ['Reinforcement Learning', 'RAG', 'Efficiency and Optimization', 'Multimodal Models']
---
The recent advancements in large language models (LLMs) and pre-trained
vision models have accelerated the development of vision-language large models
(VLLMs), enhancing the interaction between visual and linguistic modalities.
Despite their notable success across various domains, VLLMs face challenges in
modality alignment, which can lead to issues like hallucinations and unsafe
content generation. Current alignment techniques often rely on coarse feedback
and external datasets, limiting scalability and performance. In this paper, we
propose FiSAO (Fine-Grained Self-Alignment Optimization), a novel
self-alignment method that utilizes the model's own visual encoder as a
fine-grained verifier to improve vision-language alignment without the need for
additional data. By leveraging token-level feedback from the vision encoder,
FiSAO significantly improves vision-language alignment, even surpassing
traditional preference tuning methods that require additional data. Through
both theoretical analysis and experimental validation, we demonstrate that
FiSAO effectively addresses the misalignment problem in VLLMs, marking the
first instance of token-level rewards being applied to such models.
