---
layout: publication
title: 'Transmamba: Fast Universal Architecture Adaption From Transformers To Mamba'
authors: Xiuwei Chen, Sihao Lin, Xiao Dong, Zisheng Chen, Meng Cao, Jianhua Han, Hang Xu, Xiaodan Liang
conference: "Arxiv"
year: 2025
bibkey: chen2025fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15130"}
tags: ['Transformer', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models', 'Distillation']
---
Transformers have been favored in both uni-modal and multi-modal foundation
models for their flexible scalability in attention modules. Consequently, a
number of pre-trained Transformer models, e.g., LLaVA, CLIP, and DEIT, are
publicly available. Recent research has introduced subquadratic architectures
like Mamba, which enables global awareness with linear complexity.
Nevertheless, training specialized subquadratic architectures from scratch for
certain tasks is both resource-intensive and time-consuming. As a motivator, we
explore cross-architecture training to transfer the ready knowledge in existing
Transformer models to alternative architecture Mamba, termed TransMamba. Our
approach employs a two-stage strategy to expedite training new Mamba models,
ensuring effectiveness in across uni-modal and cross-modal tasks. Concerning
architecture disparities, we project the intermediate features into an aligned
latent space before transferring knowledge. On top of that, a Weight Subcloning
and Adaptive Bidirectional distillation method (WSAB) is introduced for
knowledge transfer without limitations on varying layer counts. For cross-modal
learning, we propose a cross-Mamba module that integrates language awareness
into Mamba's visual features, enhancing the cross-modal interaction
capabilities of Mamba architecture. Despite using less than 75% of the training
data typically required for training from scratch, TransMamba boasts
substantially stronger performance across various network architectures and
downstream tasks, including image classification, visual question answering,
and text-video retrieval. The code will be publicly available.
