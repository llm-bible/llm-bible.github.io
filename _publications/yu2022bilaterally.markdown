---
layout: publication
title: 'Bilaterally Slimmable Transformer For Elastic And Efficient Visual Question Answering'
authors: Zhou Yu, Zitian Jin, Jun Yu, Mingliang Xu, Hongbo Wang, Jianping Fan
conference: "Arxiv"
year: 2022
bibkey: yu2022bilaterally
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.12814"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pruning', 'Pretraining Methods', 'Transformer', 'Applications']
---
Recent advances in Transformer architectures [1] have brought remarkable
improvements to visual question answering (VQA). Nevertheless,
Transformer-based VQA models are usually deep and wide to guarantee good
performance, so they can only run on powerful GPU servers and cannot run on
capacity-restricted platforms such as mobile phones. Therefore, it is desirable
to learn an elastic VQA model that supports adaptive pruning at runtime to meet
the efficiency constraints of different platforms. To this end, we present the
bilaterally slimmable Transformer (BST), a general framework that can be
seamlessly integrated into arbitrary Transformer-based VQA models to train a
single model once and obtain various slimmed submodels of different widths and
depths. To verify the effectiveness and generality of this method, we integrate
the proposed BST framework with three typical Transformer-based VQA approaches,
namely MCAN [2], UNITER [3], and CLIP-ViL [4], and conduct extensive
experiments on two commonly-used benchmark datasets. In particular, one slimmed
MCAN-BST submodel achieves comparable accuracy on VQA-v2, while being 0.38x
smaller in model size and having 0.27x fewer FLOPs than the reference MCAN
model. The smallest MCAN-BST submodel only has 9M parameters and 0.16G FLOPs
during inference, making it possible to deploy it on a mobile device with less
than 60 ms latency.
