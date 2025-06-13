---
layout: publication
title: 'Self-data Distillation For Recovering Quality In Pruned Large Language Models'
authors: Vithursan Thangarasa, Ganesh Venkatesh, Mike Lasby, Nish Sinnadurai, Sean Lie
conference: "Arxiv"
year: 2024
bibkey: thangarasa2024self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.09982'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Merging', 'Fine-Tuning', 'Pruning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models have driven significant progress in natural language processing, but their deployment requires substantial compute and memory resources. As models scale, compression techniques become essential for balancing model quality with computational efficiency. Structured pruning, which removes less critical components of the model, is a promising strategy for reducing complexity. However, one-shot pruning often results in significant quality degradation, particularly in tasks requiring multi-step reasoning. To recover lost quality, supervised fine-tuning (SFT) is commonly applied, but it can lead to catastrophic forgetting by shifting the model's learned data distribution. Therefore, addressing the degradation from both pruning and SFT is essential to preserve the original model's quality. In this work, we utilize self-data distilled fine-tuning to address these challenges. Our approach leverages the original, unpruned model to generate a distilled dataset that preserves semantic richness and mitigates catastrophic forgetting by maintaining alignment with the base model's knowledge. Empirically, we demonstrate that self-data distillation consistently outperforms standard SFT, improving average accuracy by up to 8% on the HuggingFace OpenLLM Leaderboard v1. Specifically, when pruning six decoder blocks on Llama3.1-8B Instruct (i.e., 32 to 26 layers, reducing the model size from 8.03B to 6.72B parameters), our method retains 91.2% of the original model's accuracy compared to 81.7% with SFT, while reducing real-world FLOPs by 16.3%. Furthermore, combining self-data distilled models through model merging yields enhanced quality retention. Additionally, leveraging these pruned models in speculative decoding increases token acceptance rates, thereby improving inference efficiency in applied settings.
