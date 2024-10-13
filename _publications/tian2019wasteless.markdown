---
layout: publication
title: 'Waldorf: Wasteless Language-model Distillation On Reading-comprehension'
authors: Tian James Yi, Kreuzer Alexander P., Chen Pai-hung, Will Hans-martin
conference: "Arxiv"
year: 2019
bibkey: tian2019wasteless
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1912.06638"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Transformer based Very Large Language Models (VLLMs) like BERT, XLNet and
RoBERTa, have recently shown tremendous performance on a large variety of
Natural Language Understanding (NLU) tasks. However, due to their size, these
VLLMs are extremely resource intensive and cumbersome to deploy at production
time. Several recent publications have looked into various ways to distil
knowledge from a transformer based VLLM (most commonly BERT-Base) into a
smaller model which can run much faster at inference time. Here, we propose a
novel set of techniques which together produce a task-specific hybrid
convolutional and transformer model, WaLDORf, that achieves state-of-the-art
inference speed while still being more accurate than previous distilled models.
