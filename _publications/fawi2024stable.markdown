---
layout: publication
title: Curlora Stable LLM Continual Fine-tuning And Catastrophic Forgetting Mitigation
authors: Fawi Muhammad
conference: "Arxiv"
year: 2024
bibkey: fawi2024stable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14572"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
This paper introduces CURLoRA a novel approach to fine-tuning large language models (LLMs) that leverages CUR matrix decomposition in the context of Low-Rank Adaptation (LoRA). Our method addresses two critical challenges in LLM fine-tuning mitigating catastrophic forgetting during continual learning and reducing the number of trainable parameters. We propose a unique modification to the CUR decomposition process utilizing inverted probabilities for column and row selection which acts as an implicit regularization and initializing the U matrix as a zero matrix and only fine-tuning it. We demonstrate through experiments on multiple datasets that CURLoRA outperforms standard LoRA in mitigating catastrophic forgetting. It maintains model stability and performance across tasks while significantly reducing the number of trainable parameters. Our results show that CURLoRA achieves very good and stable task accuracy while maintaining base models perplexity scores fixed compared to LoRA upon continual fine-tuning particularly in scenarios with limited data.
