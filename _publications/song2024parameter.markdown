---
layout: publication
title: 'Sharelora: Parameter Efficient And Robust Large Language Model Fine-tuning Via Shared Low-rank Adaptation'
authors: Yurun Song, Junchen Zhao, Ian G. Harris, Sangeetha Abdu Jyothi
conference: "Arxiv"
year: 2024
bibkey: song2024parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10785"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'BERT', 'Few-Shot']
---
In this paper, we introduce \textbf\{Share\}d \textbf\{Lo\}w \textbf\{R\}ank \textbf\{A\}daptation (ShareLoRA), a Large Language Model (LLM) fine-tuning technique that balances parameter efficiency, adaptability, and robustness without compromising performance. By strategically sharing the low-rank weight matrices across different layers, ShareLoRA achieves 44% to 96% reduction in trainable parameters compared to standard LoRA, alongside a substantial decrease in memory overhead. This efficiency gain scales with model size, making ShareLoRA particularly advantageous for resource-constrained environments. Importantly, ShareLoRA not only maintains model performance but also exhibits robustness in both classification and generation tasks across diverse models, including RoBERTa, GPT-2, and LLaMA series (1, 2, and 3). It consistently outperforms LoRA in zero-shot, few-shot, and continual fine-tuning scenarios, achieving up to 1.2% average accuracy improvement, and enhanced generalization across domains. In continual learning settings, ShareLoRA achieves 1.2% higher accuracy on GSM8K, 0.6% on HumanEval, and 0.5% on both MMLU and MMLU-Pro. Our results demonstrate that ShareLoRA supports high-quality fine-tuning while offering strong generalization and continual adaptation across various model scales and diverse tasks.
