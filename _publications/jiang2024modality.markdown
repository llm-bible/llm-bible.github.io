---
layout: publication
title: 'Modality-fair Preference Optimization For Trustworthy MLLM Alignment'
authors: Songtao Jiang, Yan Zhang, Ruizhe Chen, Yeying Jin, Zuozhu Liu
conference: "Arxiv"
year: 2024
bibkey: jiang2024modality
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.15334'}
tags: ['Efficiency and Optimization', 'GPT', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias']
---
Direct Preference Optimization (DPO) is effective for aligning large language
models (LLMs), but when applied to multimodal models (MLLMs), it often favors
text over image information, leading to unreliable outputs and visual
hallucinations. To address this, we propose Modality-Fair Preference
Optimization (MFPO) to balance text and image preferences. First, we found that
the lack of image-related rewards in preference data biases optimization toward
text, so we created automated, fine-grained image preference data to correct
this. Then, we designed a learning objective to ensure the model captures both
text and image preferences while maintaining high-quality outputs. Finally, we
use a multi-stage alignment approach to stabilize training and improve learning
across both modalities. Extensive experiments demonstrate that MFPO
significantly enhances MLLM trustworthiness. On models like LLaVA-v1.5 (7B,
13B), our approach reduces hallucinations substantially. On the 7B model, MFPO
outperforms GPT-4V and achieves a nearly 40% improvement over previous methods
on Object HalBench, as well as achieving state-of-the-art performance on both
Object HalBench and AMBER when combined with the latest LLaVA-v1.6. Code will
be released.
