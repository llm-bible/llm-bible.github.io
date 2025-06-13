---
layout: publication
title: 'What Makes For Good Visual Tokenizers For Large Language Models?'
authors: Guangzhi Wang, Yixiao Ge, Xiaohan Ding, Mohan Kankanhalli, Ying Shan
conference: "Arxiv"
year: 2023
bibkey: wang2023what
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.12223'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
We empirically investigate proper pre-training methods to build good visual
tokenizers, making Large Language Models (LLMs) powerful Multimodal Large
Language Models (MLLMs). In our benchmark, which is curated to evaluate MLLMs
visual semantic understanding and fine-grained perception capabilities, we
discussed different visual tokenizers pre-trained with dominant methods (i.e.,
DeiT, CLIP, MAE, DINO), and observe that: i) Fully/weakly supervised models
capture more semantics than self-supervised models, but the gap is narrowed by
scaling up the pre-training dataset. ii) Self-supervised models are better at
fine-grained perception, where patch-level supervision is particularly
effective. iii) Tuning the visual tokenizer leads to the loss of semantics
obtained from large-scale pretraining, which is unfavorable with relatively
small-scale instruction-tuning dataset. Given the findings, we reviewed methods
that attempted to unify semantics and fine-grained visual understanding, e.g.,
patch-level feature distillation with semantically-rich targets. We obtain an
intriguing insight mask-based strategies that were once all the rage may not be
applicable for obtaining good visual tokenizers. Based on this critical
observation, we obtain a new MLLM equipped with a tailored Good Visual
Tokenizer (GVT), which exhibits strong visual comprehension capability at
multiple scales. In particular, without introducing extra parameters and
task-specific fine-tuning, GVT achieves superior performance on visual question
answering, image captioning, and other fine-grained visual understanding tasks
such as object counting and multi-class identification.
