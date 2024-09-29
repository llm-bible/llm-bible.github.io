---
layout: publication
title: "Extremely Small BERT Models From Mixed-vocabulary Training"
authors: Zhao Sanqiang, Gupta Raghav, Song Yang, Zhou Denny
conference: "Arxiv"
year: 2019
bibkey: zhao2019extremely
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.11687"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Quantization', 'Training Techniques']
---
Pretrained language models like BERT have achieved good results on NLP tasks but are impractical on resource-limited devices due to memory footprint. A large fraction of this footprint comes from the input embeddings with large input vocabulary and embedding dimensions. Existing knowledge distillation methods used for model compression cannot be directly applied to train student models with reduced vocabulary sizes. To this end we propose a distillation method to align the teacher and student embeddings via mixed-vocabulary training. Our method compresses BERT-LARGE to a task-agnostic model with smaller vocabulary and hidden dimensions which is an order of magnitude smaller than other distilled BERT models and offers a better size-accuracy trade-off on language understanding benchmarks as well as a practical dialogue task.
