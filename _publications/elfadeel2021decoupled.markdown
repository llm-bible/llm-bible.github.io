---
layout: publication
title: 'Decoupled Transformer For Scalable Inference In Open-domain Question Answering'
authors: Haytham Elfadeel, Stan Peshterliev
conference: "Arxiv"
year: 2021
bibkey: elfadeel2021decoupled
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.02765"}
tags: ['Transformer', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Pretraining Methods', 'BERT', 'Distillation']
---
Large transformer models, such as BERT, achieve state-of-the-art results in
machine reading comprehension (MRC) for open-domain question answering (QA).
However, transformers have a high computational cost for inference which makes
them hard to apply to online QA systems for applications like voice assistants.
To reduce computational cost and latency, we propose decoupling the transformer
MRC model into input-component and cross-component. The decoupling allows for
part of the representation computation to be performed offline and cached for
online use. To retain the decoupled transformer accuracy, we devised a
knowledge distillation objective from a standard transformer model. Moreover,
we introduce learned representation compression layers which help reduce by
four times the storage requirement for the cache. In experiments on the SQUAD
2.0 dataset, a decoupled transformer reduces the computational cost and latency
of open-domain MRC by 30-40% with only 1.2 points worse F1-score compared to a
standard transformer.
