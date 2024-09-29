---
layout: publication
title: Compresso: Structured Pruning With Collaborative Prompting Learns Compact Large Language Models
authors: Guo Song, Xu Jiahang, Zhang Li Lyna, Yang Mao
conference: "Arxiv"
year: 2023
bibkey: guo2023structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05015"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Prompting', 'Pruning', 'Quantization', 'Reinforcement Learning', 'Training Techniques']
---
Despite the remarkable success of Large Language Models (LLMs) the massive size poses significant deployment challenges particularly on resource-constrained hardware. While existing LLM compression methods focus on quantization pruning remains relatively unexplored due to the high cost of training-based approaches and data collection challenges. One-shot pruning methods although cost-effective and data-free have become dominant in LLM pruning but lead to performance decline under the structured pruning setting. In this work we introduce a new paradigm for structurally pruning LLMs called Compresso. Our approach through the collaboration of the proposed resource-efficient pruning algorithm and the LLM itself learns optimal pruning decisions during the training process. Compresso addresses the challenges of expensive training costs and data collection by incorporating Low-Rank Adaptation (LoRA) into the L_0 regularization during the instruction tuning process. Then we further augment the pruning algorithm by introducing a collaborative prompt that fosters collaboration between the LLM and the pruning algorithm significantly boosting the overall performance. To this end Compresso prunes LLaMA-7B to 5.4B maintaining original performance and even surpassing LLaMA-7B in reading comprehension by 2.6237;. Extensive experiments demonstrate that Compresso significantly outperforms one-shot pruning baselines across various sparsity ratios achieving up to 2.2137; 11.4337; 7.0437; and 4.8137; higher scores on the commonsense reasoning reading comprehension MMLU and BBH benchmarks respectively.
