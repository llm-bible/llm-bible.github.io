---
layout: publication
title: 'Fine-tuning Image Transformers Using Learnable Memory'
authors: Mark Sandler, Andrey Zhmoginov, Max Vladymyrov, Andrew Jackson
conference: "Arxiv"
year: 2022
bibkey: sandler2022fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2203.15243'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Multimodal Models', 'Pretraining Methods']
---
In this paper we propose augmenting Vision Transformer models with learnable
memory tokens. Our approach allows the model to adapt to new tasks, using few
parameters, while optionally preserving its capabilities on previously learned
tasks. At each layer we introduce a set of learnable embedding vectors that
provide contextual information useful for specific datasets. We call these
"memory tokens". We show that augmenting a model with just a handful of such
tokens per layer significantly improves accuracy when compared to conventional
head-only fine-tuning, and performs only slightly below the significantly more
expensive full fine-tuning. We then propose an attention-masking approach that
enables extension to new downstream tasks, with a computation reuse. In this
setup in addition to being parameters efficient, models can execute both old
and new tasks as a part of single inference at a small incremental cost.
