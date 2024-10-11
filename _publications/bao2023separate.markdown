---
layout: publication
title: 'Separate-and-enhance: Compositional Finetuning For Text2image Diffusion Models'
authors: Bao Zhipeng, Li Yijun, Singh Krishna Kumar, Wang Yu-xiong, Hebert Martial
conference: "Arxiv"
year: 2023
bibkey: bao2023separate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06712"}
tags: ['Attention Mechanism', 'Merging', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Uncategorized']
---
Despite recent significant strides achieved by diffusion-based Text-to-Image (T2I) models, current systems are still less capable of ensuring decent compositional generation aligned with text prompts, particularly for the multi-object generation. This work illuminates the fundamental reasons for such misalignment, pinpointing issues related to low attention activation scores and mask overlaps. While previous research efforts have individually tackled these issues, we assert that a holistic approach is paramount. Thus, we propose two novel objectives, the Separate loss and the Enhance loss, that reduce object mask overlaps and maximize attention scores, respectively. Our method diverges from conventional test-time-adaptation techniques, focusing on finetuning critical parameters, which enhances scalability and generalizability. Comprehensive evaluations demonstrate the superior performance of our model in terms of image realism, text-image alignment, and adaptability, notably outperforming prominent baselines. Ultimately, this research paves the way for T2I diffusion models with enhanced compositional capacities and broader applicability.
