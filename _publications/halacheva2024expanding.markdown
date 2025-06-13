---
layout: publication
title: 'Expanding Expressivity In Transformer Models With M\"obiusattention'
authors: Anna-maria Halacheva, Mojtaba Nayyeri, Steffen Staab
conference: "Arxiv"
year: 2024
bibkey: halacheva2024expanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12175"}
tags: ['Transformer', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'BERT']
---
Attention mechanisms and Transformer architectures have revolutionized
Natural Language Processing (NLP) by enabling exceptional modeling of
long-range dependencies and capturing intricate linguistic patterns. However,
their inherent reliance on linear operations in the form of matrix
multiplications limits their ability to fully capture inter-token relationships
on their own. We propose M\"obiusAttention, a novel approach that integrates
M\"obius transformations within the attention mechanism of Transformer-based
models. M\"obius transformations are non-linear operations in spaces over
complex numbers with the ability to map between various geometries. By
incorporating these properties, M\"obiusAttention empowers models to learn more
intricate geometric relationships between tokens and capture a wider range of
information through complex-valued weight vectors. We build and pre-train a
BERT and a RoFormer version enhanced with M\"obiusAttention, which we then
finetune on the GLUE benchmark. We evaluate empirically our approach against
the baseline BERT and RoFormer models on a range of downstream tasks. Our
approach compares favorably against the baseline models, even with smaller
number of parameters suggesting the enhanced expressivity of M\"obiusAttention.
This research paves the way for exploring the potential of M\"obius
transformations in the complex projective space to enhance the expressivity and
performance of foundation models.
