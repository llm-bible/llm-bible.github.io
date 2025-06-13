---
layout: publication
title: 'Kv-distill: Nearly Lossless Learnable Context Compression For Llms'
authors: Vivek Chari, Guanghui Qin, Benjamin Van Durme
conference: "Arxiv"
year: 2025
bibkey: chari2025kv
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.10337'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Applications', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
Sequence-to-sequence tasks often benefit from long contexts, but the
quadratic complexity of self-attention in standard Transformers renders this
non-trivial. During generation, temporary representations -stored in the
so-called KV cache-account for a large portion of GPU memory usage and scale
linearly with context length. We introduce KV-Distill, a Transformer
compression framework that distills long context KV caches into significantly
shorter representations in a question-independent fashion. KV-Distill can be
trained as a parameter-efficient adaptor for pretrained models, and enables the
compression of arbitrary spans of a context while preserving pre-trained model
capabilities. We treat a compressed-uncompressed cache as a student-teacher
pairing and apply a KL-type divergence to match the generated outputs.
KV-Distill outperforms other compression techniques in worst-case extractive
tasks and approaches uncompressed performance in long context question
answering and summarization, and it can be fine-tuned on domain-specific
contexts to reduce lengths by up to 99% while preserving downstream
performance. We demonstrate the generalizability of KV-Distill across various
model sizes and architectures.
