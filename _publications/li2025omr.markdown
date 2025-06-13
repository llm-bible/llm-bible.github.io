---
layout: publication
title: 'Omr-diffusion:optimizing Multi-round Enhanced Training In Diffusion Models For Improved Intent Understanding'
authors: Kun Li, Jianhui Wang, Miao Zhang, Xueqian Wang
conference: "Arxiv"
year: 2025
bibkey: li2025omr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17660"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Prompting']
---
Generative AI has significantly advanced text-driven image generation, but it
still faces challenges in producing outputs that consistently align with
evolving user preferences and intents, particularly in multi-turn dialogue
scenarios. In this research, We present a Visual Co-Adaptation (VCA) framework
that incorporates human-in-the-loop feedback, utilizing a well-trained reward
model specifically designed to closely align with human preferences. Using a
diverse multi-turn dialogue dataset, the framework applies multiple reward
functions (such as diversity, consistency, and preference feedback) to refine
the diffusion model through LoRA, effectively optimizing image generation based
on user input. We also constructed multi-round dialogue datasets with prompts
and image pairs that well-fit user intent. Experiments show the model achieves
508 wins in human evaluation, outperforming DALL-E 3 (463 wins) and others. It
also achieves 3.4 rounds in dialogue efficiency (vs. 13.7 for DALL-E 3) and
excels in metrics like LPIPS (0.15) and BLIP (0.59). Various experiments
demonstrate the effectiveness of the proposed method over state-of-the-art
baselines, with significant improvements in image consistency and alignment
with user intent.
