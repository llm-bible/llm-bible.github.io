---
layout: publication
title: 'Distill Not Only Data But Also Rewards: Can Smaller Language Models Surpass Larger Ones?'
authors: Yudi Zhang, Lu Wang, Meng Fang, Yali Du, Chenghua Huang, Jun Wang, Qingwei Lin, Mykola Pechenizkiy, Dongmei Zhang, Saravan Rajmohan, Qi Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025distill
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19557"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Ethics and Bias', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
Distilling large language models (LLMs) typically involves transferring the
teacher model's responses through supervised fine-tuning (SFT). However, this
approach neglects the potential to distill both data (output content) and
reward signals (quality evaluations). Extracting reliable reward signals
directly from teacher models is challenging, as LLMs are optimized for
generation rather than evaluation, often resulting in biased or inconsistent
assessments. To address this limitation, we propose a novel distillation
pipeline that transfers both responses and rewards. Our method generates
pseudo-rewards through a self-supervised mechanism that leverages the inherent
structure of both teacher and student responses, enabling reward learning
without explicit external evaluation. The reward model subsequently guides
reinforcement learning (RL), allowing iterative refinement of the student model
after an SFT warm-up phase. Experiments on GSM8K and MMLU-PRO demonstrate that
our method consistently outperforms traditional SFT-based approaches, enabling
student models to surpass the performance of their teachers. This work
highlights the potential for scalable, efficient distillation through
structured self-supervised reward learning, reducing dependence on external
reward supervision.
