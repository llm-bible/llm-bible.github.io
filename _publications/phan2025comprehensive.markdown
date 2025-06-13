---
layout: publication
title: 'Vnjptranslate: A Comprehensive Pipeline For Vietnamese-japanese Translation'
authors: Hoang Hai Phan, Nguyen Duc Minh Vu, Nam Dang Phuong
conference: "Arxiv"
year: 2025
bibkey: phan2025comprehensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.00339"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Prompting', 'Applications']
---
Neural Machine Translation (NMT) driven by Transformer architectures has
advanced significantly, yet faces challenges with low-resource language pairs
like Vietnamese-Japanese (Vi-Ja). Issues include sparse parallel data and
handling linguistic/cultural nuances. Recent progress in Large Language Models
(LLMs) with strong reasoning, often refined via Reinforcement Learning (RL),
enables high-quality synthetic data generation. We introduce VNJPTranslate, a
pipeline designed to systematically address the Vi-Ja translation task. It
features a targeted data augmentation strategy using advanced LLMs with
Chain-of-Thought prompting for challenging segments identified via corpus
analysis. Subsequently, we employ efficient fine-tuning techniques (Unsloth
with QLoRA) on a capable, low-parameter autoregressive model (specifically, a
fine-tuned version of the 1.8B parameter Sailor model, which is based on the
Qwen architecture) to create a practical and high-performing translation
system. This integrated approach aims to improve Vi-Ja translation quality
significantly over existing baselines.
