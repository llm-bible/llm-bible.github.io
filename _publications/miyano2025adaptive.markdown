---
layout: publication
title: 'Adaptive Lora Merge With Parameter Pruning For Low-resource Generation'
authors: Ryota Miyano, Yuki Arase
conference: "Arxiv"
year: 2025
bibkey: miyano2025adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24174"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pruning', 'Pretraining Methods', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
This study proposes a simple yet effective LoRA merge method to achieve LLM adaptation for low-resource language generation tasks. The LoRA merge technique, which integrates multiple LoRA modules trained on different tasks, has gained attention as an effective and efficient approach for adapting LLMs to target tasks. However, previous methods are limited in adaptability as they keep the LoRA parameters frozen. Additionally, the low-resource problem has been out of their scope. We propose a LoRA merge method that updates and prunes LoRA parameters through fine-tuning with minimal target task data, which allows finer-grained adjustments of LoRA parameters and enhancement of task adaptability. Extensive experiments have been conducted taking summarization as a benchmark task. Our datasets cover various domains and multiple languages of English and Japanese. The results confirm that the proposed method achieves significant and consistent improvements in task adaptability over the previous methods.
