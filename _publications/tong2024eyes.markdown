---
layout: publication
title: Eyes Wide Shut Exploring The Visual Shortcomings Of Multimodal Llms
authors: Tong Shengbang, Liu Zhuang, Zhai Yuexiang, Ma Yi, Lecun Yann, Xie Saining
conference: "Arxiv"
year: 2024
bibkey: tong2024eyes
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06209"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'Training Techniques']
---
Is vision good enough for language Recent advancements in multimodal models primarily stem from the powerful reasoning abilities of large language models (LLMs). However the visual component typically depends only on the instance45;level contrastive language45;image pre45;training (CLIP). Our research reveals that the visual capabilities in recent multimodal LLMs (MLLMs) still exhibit systematic shortcomings. To understand the roots of these errors we explore the gap between the visual embedding space of CLIP and vision45;only self45;supervised learning. We identify CLIP45;blind pairs 45; images that CLIP perceives as similar despite their clear visual differences. With these pairs we construct the Multimodal Visual Patterns (MMVP) benchmark. MMVP exposes areas where state45;of45;the45;art systems including GPT45;4V struggle with straightforward questions across nine basic visual patterns often providing incorrect answers and hallucinated explanations. We further evaluate various CLIP45;based vision45;and45;language models and found a notable correlation between visual patterns that challenge CLIP models and those problematic for multimodal LLMs. As an initial effort to address these issues we propose a Mixture of Features (MoF) approach demonstrating that integrating vision self45;supervised learning features with MLLMs can significantly enhance their visual grounding capabilities. Together our research suggests visual representation learning remains an open challenge and accurate visual grounding is crucial for future successful multimodal systems.
