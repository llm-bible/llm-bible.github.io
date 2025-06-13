---
layout: publication
title: 'In-context Edit: Enabling Instructional Image Editing With In-context Generation In Large Scale Diffusion Transformer'
authors: Zechuan Zhang, Ji Xie, Yu Lu, Zongxin Yang, Yi Yang
conference: "Arxiv"
year: 2025
bibkey: zhang2025enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20690"}
  - {name: "Code", url: "https://river-zhang.github.io/ICEdit-gh-pages/"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Merging', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Instruction-based image editing enables robust image modification via natural
language prompts, yet current methods face a precision-efficiency tradeoff.
Fine-tuning methods demand significant computational resources and large
datasets, while training-free techniques struggle with instruction
comprehension and edit quality. We resolve this dilemma by leveraging
large-scale Diffusion Transformer (DiT)' enhanced generation capacity and
native contextual awareness. Our solution introduces three contributions: (1)
an in-context editing framework for zero-shot instruction compliance using
in-context prompting, avoiding structural changes; (2) a LoRA-MoE hybrid tuning
strategy that enhances flexibility with efficient adaptation and dynamic expert
routing, without extensive retraining; and (3) an early filter inference-time
scaling method using vision-language models (VLMs) to select better initial
noise early, improving edit quality. Extensive evaluations demonstrate our
method's superiority: it outperforms state-of-the-art approaches while
requiring only 0.5% training data and 1% trainable parameters compared to
conventional baselines. This work establishes a new paradigm that enables
high-precision yet efficient instruction-guided editing. Codes and demos can be
found in https://river-zhang.github.io/ICEdit-gh-pages/.
