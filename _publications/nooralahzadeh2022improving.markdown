---
layout: publication
title: 'Improving The Cross-lingual Generalisation In Visual Question Answering'
authors: Farhad Nooralahzadeh, Rico Sennrich
conference: "Arxiv"
year: 2022
bibkey: nooralahzadeh2022improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.02982"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Applications']
---
While several benefits were realized for multilingual vision-language
pretrained models, recent benchmarks across various tasks and languages showed
poor cross-lingual generalisation when multilingually pre-trained
vision-language models are applied to non-English data, with a large gap
between (supervised) English performance and (zero-shot) cross-lingual
transfer. In this work, we explore the poor performance of these models on a
zero-shot cross-lingual visual question answering (VQA) task, where models are
fine-tuned on English visual-question data and evaluated on 7 typologically
diverse languages. We improve cross-lingual transfer with three strategies: (1)
we introduce a linguistic prior objective to augment the cross-entropy loss
with a similarity-based loss to guide the model during training, (2) we learn a
task-specific subnetwork that improves cross-lingual generalisation and reduces
variance without model modification, (3) we augment training examples using
synthetic code-mixing to promote alignment of embeddings between source and
target languages. Our experiments on xGQA using the pretrained multilingual
multimodal transformers UC2 and M3P demonstrate the consistent effectiveness of
the proposed fine-tuning strategy for 7 languages, outperforming existing
transfer methods with sparse models. Code and data to reproduce our findings
are publicly available.
