---
layout: publication
title: 'Bottleneck Low-rank Transformers For Low-resource Spoken Language Understanding'
authors: Pu Wang, Hugo Van Hamme
conference: "Arxiv"
year: 2022
bibkey: wang2022bottleneck
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.14318"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Applications', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'BERT']
---
End-to-end spoken language understanding (SLU) systems benefit from
pretraining on large corpora, followed by fine-tuning on application-specific
data. The resulting models are too large for on-edge applications. For
instance, BERT-based systems contain over 110M parameters. Observing the model
is overparameterized, we propose lean transformer structure where the dimension
of the attention mechanism is automatically reduced using group sparsity. We
propose a variant where the learned attention subspace is transferred to an
attention bottleneck layer. In a low-resource setting and without pre-training,
the resulting compact SLU model achieves accuracies competitive with
pre-trained large models.
