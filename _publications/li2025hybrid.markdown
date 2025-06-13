---
layout: publication
title: 'Matvlm: Hybrid Mamba-transformer For Efficient Vision-language Modeling'
authors: Yingyue Li, Bencheng Liao, Wenyu Liu, Xinggang Wang
conference: "Arxiv"
year: 2025
bibkey: li2025hybrid
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13440'}
  - {name: "Code", url: 'http://github.com/hustvl/MaTVLM'}
tags: ['Attention Mechanism', 'Has Code', 'Language Modeling', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Model Architecture', 'Tools', 'Training Techniques', 'Merging', 'Multimodal Models', 'Pretraining Methods']
---
With the advancement of RNN models with linear complexity, the quadratic
complexity challenge of transformers has the potential to be overcome. Notably,
the emerging Mamba-2 has demonstrated competitive performance, bridging the gap
between RNN models and transformers. However, due to sequential processing and
vanishing gradients, RNN models struggle to capture long-range dependencies,
limiting contextual understanding. This results in slow convergence, high
resource demands, and poor performance on downstream understanding and complex
reasoning tasks. In this work, we present a hybrid model MaTVLM by substituting
a portion of the transformer decoder layers in a pre-trained VLM with Mamba-2
layers. Leveraging the inherent relationship between attention and Mamba-2, we
initialize Mamba-2 with corresponding attention weights to accelerate
convergence. Subsequently, we employ a single-stage distillation process, using
the pre-trained VLM as the teacher model to transfer knowledge to the MaTVLM,
further enhancing convergence speed and performance. Furthermore, we
investigate the impact of differential distillation loss within our training
framework. We evaluate the MaTVLM on multiple benchmarks, demonstrating
competitive performance against the teacher model and existing VLMs while
surpassing both Mamba-based VLMs and models of comparable parameter scales.
Remarkably, the MaTVLM achieves up to 3.6x faster inference than the teacher
model while reducing GPU memory consumption by 27.5%, all without compromising
performance. Code and models are released at http://github.com/hustvl/MaTVLM.
