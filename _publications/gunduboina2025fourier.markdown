---
layout: publication
title: 'Frogdognet: Fourier Frequency Retained Visual Prompt Output Guidance For Domain Generalization Of CLIP In Remote Sensing'
authors: Hariseetharam Gunduboina, Muhammad Haris Khan, Biplab Banerjee
conference: "Arxiv"
year: 2025
bibkey: gunduboina2025fourier
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16433"}
  - {name: "Code", url: "https://github.com/HariseetharamG/FrogDogNet"}
tags: ['Transformer', 'Tools', 'Applications', 'Model Architecture', 'Attention Mechanism', 'Has Code', 'Multimodal Models', 'Prompting']
---
In recent years, large-scale vision-language models (VLMs) like CLIP have
gained attention for their zero-shot inference using instructional text
prompts. While these models excel in general computer vision, their potential
for domain generalization in remote sensing (RS) remains underexplored.
Existing approaches enhance prompt learning by generating visual prompt tokens
but rely on full-image features, introducing noise and background artifacts
that vary within a class, causing misclassification. To address this, we
propose FrogDogNet, a novel prompt learning framework integrating Fourier
frequency filtering and self-attention to improve RS scene classification and
domain generalization. FrogDogNet selectively retains invariant low-frequency
components while eliminating noise and irrelevant backgrounds, ensuring robust
feature representation across domains. The model first extracts significant
features via projection and self-attention, then applies frequency-based
filtering to preserve essential structural information for prompt learning.
Extensive experiments on four RS datasets and three domain generalization tasks
show that FrogDogNet consistently outperforms state-of-the-art prompt learning
methods, demonstrating superior adaptability across domain shifts. Our findings
highlight the effectiveness of frequency-based invariant feature retention in
generalization, paving the way for broader applications. Our code is available
at https://github.com/HariseetharamG/FrogDogNet
