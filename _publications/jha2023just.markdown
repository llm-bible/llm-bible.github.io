---
layout: publication
title: Just CHOP Embarrassingly Simple LLM Compression
authors: Jha Ananya Harsh, Sherborne Tom, Walsh Evan Pete, Groeneveld Dirk, Strubell Emma, Beltagy Iz
conference: "Arxiv"
year: 2023
bibkey: jha2023just
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14864"}
tags: ['ARXIV', 'BERT', 'Distillation', 'Efficiency And Optimization', 'LLM', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Reinforcement Learning']
---
Large language models (LLMs) enable unparalleled few- and zero-shot reasoning capabilities but at a high computational footprint. A growing assortment of methods for compression promises to reduce the computational burden of LLMs in deployment but so far only quantization approaches have been demonstrated to be effective for LLM compression while maintaining zero-shot performance. A critical step in the compression process the pretrain-then-finetune paradigm has largely been overlooked when adapting existing pruning strategies to LLMs or proposing new ones. In this work we show that embarrassingly simple layer pruning coupled with an extended language model pretraining as the finetuning phase produces state-of-the-art results against structured and even semi-structured compression of models at a 7B scale while being more inference efficient. We call this method LayerChop where we deterministically remove layers from a model followed by task-agnostic finetuning of the remaining weights by continued self-supervised pretraining. At this scale we also show how distillation which has been super effective in task-agnostic compression of smaller BERT-style models becomes inefficient against our simple pruning technique.
