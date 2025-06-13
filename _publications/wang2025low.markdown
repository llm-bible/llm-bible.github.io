---
layout: publication
title: 'Loki: Low-damage Knowledge Implanting Of Large Language Models'
authors: Runyu Wang, Peng Ping, Zhengyu Guo, Xiaoye Zhang, Quan Shi, Liting Zhou, Tianbo Ji
conference: "Arxiv"
year: 2025
bibkey: wang2025low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22120"}
  - {name: "Code", url: "https://github.com/Nexround/LoKI"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Fine-tuning adapts pretrained models for specific tasks but poses the risk of catastrophic forgetting (CF), where critical knowledge from pre-training is overwritten. Current Parameter-Efficient Fine-Tuning (PEFT) methods for Large Language Models (LLMs), while efficient, often sacrifice general capabilities. To address the issue of CF in a general-purpose PEFT framework, we propose \textbf\{Lo\}w-damage \textbf\{K\}nowledge \textbf\{I\}mplanting (\textbf\{LoKI\}), a PEFT technique that is based on a mechanistic understanding of how knowledge is stored in transformer architectures. In two real-world scenarios, LoKI demonstrates task-specific performance that is comparable to or even surpasses that of full fine-tuning and LoRA-based methods across various model types, while significantly better preserving general capabilities. Our work connects mechanistic insights into LLM knowledge storage with practical fine-tuning objectives, achieving state-of-the-art trade-offs between task specialization and the preservation of general capabilities. Our implementation is publicly available as ready-to-use code\footnote\{https://github.com/Nexround/LoKI\}.
