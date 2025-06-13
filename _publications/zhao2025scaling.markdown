---
layout: publication
title: 'Scaling Reasoning Without Attention'
authors: Xueliang Zhao, Wei Wu, Lingpeng Kong
conference: "Arxiv"
year: 2025
bibkey: zhao2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22425"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
Large language models (LLMs) have made significant advances in complex reasoning tasks, yet they remain bottlenecked by two core challenges: architectural inefficiency due to reliance on Transformers, and a lack of structured fine-tuning for high-difficulty domains. We introduce \ourmodel, an attention-free language model that addresses both issues through architectural and data-centric innovations. Built on the state space dual (SSD) layers of Mamba-2, our model eliminates the need for self-attention and key-value caching, enabling fixed-memory, constant-time inference. To train it for complex reasoning, we propose a two-phase curriculum fine-tuning strategy based on the \textsc\{PromptCoT\} synthesis paradigm, which generates pedagogically structured problems via abstract concept selection and rationale-guided generation. On benchmark evaluations, \ourmodel-7B outperforms strong Transformer and hybrid models of comparable scale, and even surpasses the much larger Gemma3-27B by 2.6% on AIME 24, 0.6% on AIME 25, and 3.0% on Livecodebench. These results highlight the potential of state space models as efficient and scalable alternatives to attention-based architectures for high-capacity reasoning.
