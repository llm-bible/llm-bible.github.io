---
layout: publication
title: 'Gora: Gradient-driven Adaptive Low Rank Adaptation'
authors: Haonan He, Peng Ye, Yuchen Ren, Yuan Yuan, Luyang Zhou, Shucun Ju, Lei Chen
conference: "Arxiv"
year: 2025
bibkey: he2025gradient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12171"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Low-Rank Adaptation (LoRA) is a crucial method for efficiently fine-tuning large language models (LLMs), with its effectiveness influenced by two key factors: rank selection and weight initialization. While numerous LoRA variants have been proposed to improve performance by addressing one of these aspects, they often compromise usability or computational efficiency. In this paper, we analyze and identify the core limitations of existing approaches and propose a novel framework -- GoRA (Gradient-driven Adaptive Low Rank Adaptation) -- that simultaneously adapts both the rank and initialization strategy within a unified framework. GoRA leverages gradient information during training to dynamically assign optimal ranks and initialize low-rank adapter weights in an adaptive manner. To our knowledge, GoRA is the first method that not only addresses the limitations of prior approaches -- which often focus on either rank selection or initialization in isolation -- but also unifies both aspects within a single framework, enabling more effective and efficient adaptation. Extensive experiments across various architectures and modalities show that GoRA consistently outperforms existing LoRA-based methods while preserving the efficiency of vanilla LoRA. For example, when fine-tuning Llama3.1-8B-Base for mathematical reasoning, GoRA achieves a 5.13-point improvement over standard LoRA and even outperforms full fine-tuning by 2.05 points under high-rank settings.
