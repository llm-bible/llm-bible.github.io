---
layout: publication
title: 'Unlocking Pretrained Llms For Motion-related Multimodal Generation: A Fine-tuning Approach To Unify Diffusion And Next-token Prediction'
authors: Shinichi Tanaka, Zhao Wang, Yoichi Kato, Jun Ohya
conference: "Arxiv"
year: 2025
bibkey: tanaka2025unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06119"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Merging', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
In this paper, we propose a unified framework that leverages a single
pretrained LLM for Motion-related Multimodal Generation, referred to as MoMug.
MoMug integrates diffusion-based continuous motion generation with the model's
inherent autoregressive discrete text prediction capabilities by fine-tuning a
pretrained LLM. This enables seamless switching between continuous motion
output and discrete text token prediction within a single model architecture,
effectively combining the strengths of both diffusion- and LLM-based
approaches. Experimental results show that, compared to the most recent
LLM-based baseline, MoMug improves FID by 38% and mean accuracy across seven
metrics by 16.61% on the text-to-motion task. Additionally, it improves mean
accuracy across eight metrics by 8.44% on the text-to-motion task. To the best
of our knowledge, this is the first approach to integrate diffusion- and
LLM-based generation within a single model for motion-related multimodal tasks
while maintaining low training costs. This establishes a foundation for future
advancements in motion-related generation, paving the way for high-quality yet
cost-efficient motion synthesis.
