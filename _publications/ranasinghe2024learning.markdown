---
layout: publication
title: 'Learning To Localize Objects Improves Spatial Reasoning In Visual-llms'
authors: Kanchana Ranasinghe, Satya Narayan Shukla, Omid Poursaeed, Michael S. Ryoo, Tsung-yu Lin
conference: "Arxiv"
year: 2024
bibkey: ranasinghe2024learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.07449'}
tags: ['Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Integration of Large Language Models (LLMs) into visual domain tasks,
resulting in visual-LLMs (V-LLMs), has enabled exceptional performance in
vision-language tasks, particularly for visual question answering (VQA).
However, existing V-LLMs (e.g. BLIP-2, LLaVA) demonstrate weak spatial
reasoning and localization awareness. Despite generating highly descriptive and
elaborate textual answers, these models fail at simple tasks like
distinguishing a left vs right location. In this work, we explore how
image-space coordinate based instruction fine-tuning objectives could inject
spatial awareness into V-LLMs. We discover optimal coordinate representations,
data-efficient instruction fine-tuning objectives, and pseudo-data generation
strategies that lead to improved spatial awareness in V-LLMs. Additionally, our
resulting model improves VQA across image and video domains, reduces undesired
hallucination, and generates better contextual object descriptions. Experiments
across 5 vision-language tasks involving 14 different datasets establish the
clear performance improvements achieved by our proposed framework.
