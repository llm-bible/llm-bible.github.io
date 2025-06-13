---
layout: publication
title: 'Freepruner: A Training-free Approach For Large Multimodal Model Acceleration'
authors: Bingxin Xu, Yuzhang Shang, Yunhao Ge, Qian Lou, Yan Yan
conference: "Arxiv"
year: 2024
bibkey: xu2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15446"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Merging', 'Quantization', 'Pretraining Methods', 'Fine-Tuning', 'Attention Mechanism']
---
Large Multimodal Models (LMMs) have demonstrated impressive capabilities in
visual-language tasks but face significant deployment challenges due to their
high computational demands. While recent token reduction methods show promise
for accelerating LMMs, they typically require extensive retraining or
fine-tuning, making them impractical for many state-of-the-art models,
especially those with proprietary training data. We propose freePruner, a
training-free token reduction approach that can be directly applied to any
open-source LMM without additional training. Unlike existing methods that rely
heavily on token merging operations, freePruner employs a two-stage token
selection strategy: (1) identifying pivotal tokens that capture high-level
semantic information using our designed contribution degree metric, and (2)
selecting complementary tokens that preserve essential low-level visual details
through attention pattern analysis. Extensive experiments demonstrate that
freePruner achieves 2x acceleration while maintaining comparable performance
across mainstream visual question-answering benchmarks in the training-free
setting. Moreover, freePruner is orthogonal to and can be combined with other
post-training acceleration techniques, such as post-training quantization,
providing a practical solution for efficient LMM deployment.
