---
layout: publication
title: 'Unveiling Instruction-specific Neurons & Experts: An Analytical Framework For Llm''s Instruction-following Capabilities'
authors: Junyan Zhang, Yubo Gao, Yibo Yan, Jungang Li, Zhaorui Hou, Sicheng Tao, Shuliang Liu, Song Dai, Yonghua Hei, Junzhuo Li, Xuming Hu
conference: "Arxiv"
year: 2025
bibkey: zhang2025unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21191"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
The finetuning of Large Language Models (LLMs) has significantly advanced their instruction-following capabilities, yet the underlying computational mechanisms driving these improvements remain poorly understood. This study systematically examines how fine-tuning reconfigures LLM computations by isolating and analyzing instruction-specific sparse components, i.e., neurons in dense models and both neurons and experts in Mixture-of-Experts (MoE) architectures. In particular, we introduce HexaInst, a carefully curated and balanced instructional dataset spanning six distinct categories, and propose SPARCOM, a novel analytical framework comprising three key contributions: (1) a method for identifying these sparse components, (2) an evaluation of their functional generality and uniqueness, and (3) a systematic comparison of their alterations. Through experiments, we demonstrate functional generality, uniqueness, and the critical role of these components in instruction execution. By elucidating the relationship between fine-tuning-induced adaptations and sparse computational substrates, this work provides deeper insights into how LLMs internalize instruction-following behavior for the trustworthy LLM community.
