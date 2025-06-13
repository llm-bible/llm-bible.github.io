---
layout: publication
title: 'Docllm: A Layout-aware Generative Language Model For Multimodal Document Understanding'
authors: Dongsheng Wang, Natraj Raman, Mathieu Sibue, Zhiqiang Ma, Petr Babkin, Simerjot Kaur, Yulong Pei, Armineh Nourbakhsh, Xiaomo Liu
conference: "Arxiv"
year: 2023
bibkey: wang2023layout
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00908"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Pre-Training', 'Attention Mechanism']
---
Enterprise documents such as forms, invoices, receipts, reports, contracts,
and other similar records, often carry rich semantics at the intersection of
textual and spatial modalities. The visual cues offered by their complex
layouts play a crucial role in comprehending these documents effectively. In
this paper, we present DocLLM, a lightweight extension to traditional large
language models (LLMs) for reasoning over visual documents, taking into account
both textual semantics and spatial layout. Our model differs from existing
multimodal LLMs by avoiding expensive image encoders and focuses exclusively on
bounding box information to incorporate the spatial layout structure.
Specifically, the cross-alignment between text and spatial modalities is
captured by decomposing the attention mechanism in classical transformers to a
set of disentangled matrices. Furthermore, we devise a pre-training objective
that learns to infill text segments. This approach allows us to address
irregular layouts and heterogeneous content frequently encountered in visual
documents. The pre-trained model is fine-tuned using a large-scale instruction
dataset, covering four core document intelligence tasks. We demonstrate that
our solution outperforms SotA LLMs on 14 out of 16 datasets across all tasks,
and generalizes well to 4 out of 5 previously unseen datasets.
