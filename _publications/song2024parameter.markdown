---
layout: publication
title: 'Sharelora: Parameter Efficient And Robust Large Language Model Fine-tuning Via Shared Low-rank Adaptation'
authors: Song Yurun, Zhao Junchen, Harris Ian G., Jyothi Sangeetha Abdu
conference: "Arxiv"
year: 2024
bibkey: song2024parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10785"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques', 'Transformer']
---
This study introduces an approach to optimize Parameter Efficient Fine Tuning (PEFT) for Pretrained Language Models (PLMs) by implementing a Shared Low Rank Adaptation (ShareLoRA). By strategically deploying ShareLoRA across different layers and adapting it for the Query, Key, and Value components of self-attention layers, we achieve a substantial reduction in the number of training parameters and memory usage. Importantly, ShareLoRA not only maintains model performance but also exhibits robustness in both classification and generation tasks across a variety of models, including RoBERTa, GPT-2, LLaMA and LLaMA2. It demonstrates superior transfer learning capabilities compared to standard LoRA applications and mitigates overfitting by sharing weights across layers. Our findings affirm that ShareLoRA effectively boosts parameter efficiency while ensuring scalable and high-quality performance across different language model architectures.
