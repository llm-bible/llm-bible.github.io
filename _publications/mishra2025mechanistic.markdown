---
layout: publication
title: 'Mechanistic Interpretability Of Gpt-like Models On Summarization Tasks'
authors: Anurag Mishra
conference: "Arxiv"
year: 2025
bibkey: mishra2025mechanistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17073"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability', 'Applications', 'Attention Mechanism']
---
Mechanistic interpretability research seeks to reveal the inner workings of large language models, yet most work focuses on classification or generative tasks rather than summarization. This paper presents an interpretability framework for analyzing how GPT-like models adapt to summarization tasks. We conduct differential analysis between pre-trained and fine-tuned models, quantifying changes in attention patterns and internal activations. By identifying specific layers and attention heads that undergo significant transformation, we locate the "summarization circuit" within the model architecture. Our findings reveal that middle layers (particularly 2, 3, and 5) exhibit the most dramatic changes, with 62% of attention heads showing decreased entropy, indicating a shift toward focused information selection. We demonstrate that targeted LoRA adaptation of these identified circuits achieves significant performance improvement over standard LoRA fine-tuning while requiring fewer training epochs. This work bridges the gap between black-box evaluation and mechanistic understanding, providing insights into how neural networks perform information selection and compression during summarization.
