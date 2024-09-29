---
layout: publication
title: Just CHOP Embarrassingly Simple LLM Compression
authors: Jha Ananya Harsh, Sherborne Tom, Walsh Evan Pete, Groeneveld Dirk, Strubell Emma, Beltagy Iz
conference: "Arxiv"
year: 2023
bibkey: jha2023just
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14864"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) enable unparalleled few45; and zero45;shot reasoning capabilities but at a high computational footprint. A growing assortment of methods for compression promises to reduce the computational burden of LLMs in deployment but so far only quantization approaches have been demonstrated to be effective for LLM compression while maintaining zero45;shot performance. A critical step in the compression process the pretrain45;then45;finetune paradigm has largely been overlooked when adapting existing pruning strategies to LLMs or proposing new ones. In this work we show that embarrassingly simple layer pruning coupled with an extended language model pretraining as the finetuning phase produces state45;of45;the45;art results against structured and even semi45;structured compression of models at a 7B scale while being more inference efficient. We call this method LayerChop where we deterministically remove layers from a model followed by task45;agnostic finetuning of the remaining weights by continued self45;supervised pretraining. At this scale we also show how distillation which has been super effective in task45;agnostic compression of smaller BERT45;style models becomes inefficient against our simple pruning technique.
