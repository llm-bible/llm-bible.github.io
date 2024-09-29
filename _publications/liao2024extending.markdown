---
layout: publication
title: 'Extending Token Computation For LLM Reasoning'
authors: Liao Bingli, Vargas Danilo Vasconcellos
conference: "Arxiv"
year: 2024
bibkey: liao2024extending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14932"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large Language Models (LLMs) are pivotal in advancing natural language processing but often struggle with complex reasoning tasks due to inefficient attention distributions. In this paper we explore the effect of increased computed tokens on LLM performance and introduce a novel method for extending computed tokens in the Chain-of-Thought (CoT) process utilizing attention mechanism optimization. By fine-tuning an LLM on a domain-specific highly structured dataset we analyze attention patterns across layers identifying inefficiencies caused by non-semantic tokens with outlier high attention scores. To address this we propose an algorithm that emulates early layer attention patterns across downstream layers to re-balance skewed attention distributions and enhance knowledge abstraction. Our findings demonstrate that our approach not only facilitates a deeper understanding of the internal dynamics of LLMs but also significantly improves their reasoning capabilities particularly in non-STEM domains. Our study lays the groundwork for further innovations in LLM design aiming to create more powerful versatile and responsible models capable of tackling a broad range of real-world applications.
