---
layout: publication
title: 'Enhancing In-context Learning Performance With Just Svd-based Weight Pruning: A Theoretical Perspective'
authors: Yao Xinhao, Hu Xiaolin, Yang Shenzhi, Liu Yong
conference: "Arxiv"
year: 2024
bibkey: yao2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03768"}
  - {name: "Code", url: "https://github.com/chen123CtrlS/EnhancingICL_SVDPruning"}
tags: ['Efficiency And Optimization', 'Has Code', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Pruning', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Pre-trained large language models (LLMs) based on Transformer have
demonstrated striking in-context learning (ICL) abilities. With a few
demonstration input-label pairs, they can predict the label for an unseen input
without any parameter updates. In this paper, we show an exciting phenomenon
that SVD-based weight pruning can enhance ICL performance, and more surprising,
pruning weights in deep layers often results in more stable performance
improvements in shallow layers. However, the underlying mechanism of those
findings still remains an open question. To reveal those findings, we conduct
an in-depth theoretical analysis by presenting the implicit gradient descent
(GD) trajectories of ICL and giving the mutual information based generalization
bounds of ICL via full implicit GD trajectories. This helps us reasonably
explain the surprising experimental findings. Besides, based on all our
experimental and theoretical insights, we intuitively propose a simple,
model-compression and derivative-free algorithm for downstream tasks in
enhancing ICL inference. Experiments on benchmark datasets and open source LLMs
display the method effectiveness\footnote\{The code is available at
\url\{https://github.com/chen123CtrlS/EnhancingICL_SVDPruning\}\}.
