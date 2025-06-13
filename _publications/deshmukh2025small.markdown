---
layout: publication
title: 'Mellow: A Small Audio Language Model For Reasoning'
authors: Soham Deshmukh, Satvik Dixit, Rita Singh, Bhiksha Raj
conference: "Arxiv"
year: 2025
bibkey: deshmukh2025small
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.08540'}
tags: ['Training Techniques', 'Multimodal Models', 'Applications', 'Pretraining Methods']
---
Multimodal Audio-Language Models (ALMs) can understand and reason over both
audio and text. Typically, reasoning performance correlates with model size,
with the best results achieved by models exceeding 8 billion parameters.
However, no prior work has explored enabling small audio-language models to
perform reasoning tasks, despite the potential applications for edge devices.
To address this gap, we introduce Mellow, a small Audio-Language Model
specifically designed for reasoning. Mellow achieves state-of-the-art
performance among existing small audio-language models and surpasses several
larger models in reasoning capabilities. For instance, Mellow scores 52.11 on
MMAU, comparable to SoTA Qwen2 Audio (which scores 52.5) while using 50 times
fewer parameters and being trained on 60 times less data (audio hrs). To train
Mellow, we introduce ReasonAQA, a dataset designed to enhance audio-grounded
reasoning in models. It consists of a mixture of existing datasets (30% of the
data) and synthetically generated data (70%). The synthetic dataset is derived
from audio captioning datasets, where Large Language Models (LLMs) generate
detailed and multiple-choice questions focusing on audio events, objects,
acoustic scenes, signal properties, semantics, and listener emotions. To
evaluate Mellow's reasoning ability, we benchmark it on a diverse set of tasks,
assessing on both in-distribution and out-of-distribution data, including audio
understanding, deductive reasoning, and comparative reasoning. Finally, we
conduct extensive ablation studies to explore the impact of projection layer
choices, synthetic data generation methods, and language model pretraining on
reasoning performance. Our training dataset, findings, and baseline pave the
way for developing small ALMs capable of reasoning.
