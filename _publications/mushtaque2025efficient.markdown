---
layout: publication
title: 'An Efficient Attention Mechanism For Sequential Recommendation Tasks: Hydrarec'
authors: Uzma Mushtaque
conference: "Arxiv"
year: 2025
bibkey: mushtaque2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01242"}
tags: ['Multimodal Models', 'Model Architecture', 'RecSys', 'Pretraining Methods', 'BERT', 'Transformer', 'Attention Mechanism']
---
Transformer based models are increasingly being used in various domains
including recommender systems (RS). Pretrained transformer models such as BERT
have shown good performance at language modelling. With the greater ability to
model sequential tasks, variants of Encoder-only models (like BERT4Rec, SASRec
etc.) have found success in sequential RS problems. Computing dot-product
attention in traditional transformer models has quadratic complexity in
sequence length. This is a bigger problem with RS because unlike language
models, new items are added to the catalogue every day. User buying history is
a dynamic sequence which depends on multiple factors. Recently, various linear
attention models have tried to solve this problem by making the model linear in
sequence length (token dimensions). Hydra attention is one such linear
complexity model proposed for vision transformers which reduces the complexity
of attention for both the number of tokens as well as model embedding
dimensions. Building on the idea of Hydra attention, we introduce an efficient
Transformer based Sequential RS (HydraRec) which significantly improves
theoretical complexity of computing attention for longer sequences and bigger
datasets while preserving the temporal context. Extensive experiments are
conducted to evaluate other linear transformer-based RS models and compared
with HydraRec across various evaluation metrics. HydraRec outperforms other
linear attention-based models as well as dot-product based attention models
when used with causal masking for sequential recommendation next item
prediction tasks. For bi-directional models its performance is comparable to
the BERT4Rec model with an improvement in running time.
