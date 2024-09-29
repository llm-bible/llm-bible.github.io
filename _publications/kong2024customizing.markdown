---
layout: publication
title: 'Customizing Language Models With Instance-wise Lora For Sequential Recommendation'
authors: Kong Xiaoyu, Wu Jiancan, Zhang An, Sheng Leheng, Lin Hui, Wang Xiang, He Xiangnan
conference: "Arxiv"
year: 2024
bibkey: kong2024customizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10159"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Sequential recommendation systems predict a users next item of interest by analyzing past interactions aligning recommendations with individual preferences. Leveraging the strengths of Large Language Models (LLMs) in knowledge comprehension and reasoning recent approaches have applied LLMs to sequential recommendation through language generation paradigms. These methods convert user behavior sequences into prompts for LLM fine-tuning utilizing Low-Rank Adaptation (LoRA) modules to refine recommendations. However the uniform application of LoRA across diverse user behaviors sometimes fails to capture individual variability leading to suboptimal performance and negative transfer between disparate sequences. To address these challenges we propose Instance-wise LoRA (iLoRA) integrating LoRA with the Mixture of Experts (MoE) framework. iLoRA creates a diverse array of experts each capturing specific aspects of user preferences and introduces a sequence representation guided gate function. This gate function processes historical interaction sequences to generate enriched representations guiding the gating network to output customized expert participation weights. This tailored approach mitigates negative transfer and dynamically adjusts to diverse behavior patterns. Extensive experiments on three benchmark datasets demonstrate the effectiveness of iLoRA highlighting its superior performance compared to existing methods in capturing user-specific preferences and improving recommendation accuracy.
