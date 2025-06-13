---
layout: publication
title: 'QID: Efficient Query-informed Vits In Data-scarce Regimes For Ocr-free Visual Document Understanding'
authors: Binh M. Le, Shaoyuan Xu, Jinmiao Fu, Zhishen Huang, Moyan Li, Yanhui Guo, Hongdong Li, Sameera Ramasinghe, Bryan Wang
conference: "Arxiv"
year: 2025
bibkey: le2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.02971'}
tags: ['Attention Mechanism', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
In Visual Document Understanding (VDU) tasks, fine-tuning a pre-trained
Vision-Language Model (VLM) with new datasets often falls short in optimizing
the vision encoder to identify query-specific regions in text-rich document
images. Existing methods that directly inject queries into model layers by
modifying the network architecture often struggle to adapt to new datasets with
limited annotations. To address this, we introduce QID, a novel, streamlined,
architecture-preserving approach that integrates query embeddings into the
vision encoder, leading to notable performance gains, particularly in
data-scarce fine-tuning scenarios. Specifically, our approach introduces a
dual-module framework: a query-aware module that generates a unique query
vector to precisely guide the model's focus, as well as a query-agnostic module
that captures the positional relationships among tokens, ensuring robust
spatial understanding. Notably, both modules operate independently of the
vision attention blocks, facilitating targeted learning of query embeddings and
enhancing visual semantic identification. Experiments with OCR-free VLMs across
multiple datasets demonstrate significant performance improvements using our
method, especially in handling text-rich documents in data-scarce environments.
