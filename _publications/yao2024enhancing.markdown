---
layout: publication
title: Enhancing In45;context Learning Performance With Just Svd45;based Weight Pruning A Theoretical Perspective
authors: Yao Xinhao, Hu Xiaolin, Yang Shenzhi, Liu Yong
conference: "Arxiv"
year: 2024
bibkey: yao2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03768"}
  - {name: "Code", url: "https://github.com/chen123CtrlS/EnhancingICL&#95;SVDPruning&#125;&#125;"}
tags: ['Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Pre45;trained large language models (LLMs) based on Transformer have demonstrated striking in45;context learning (ICL) abilities. With a few demonstration input45;label pairs they can predict the label for an unseen input without any parameter updates. In this paper we show an exciting phenomenon that SVD45;based weight pruning can enhance ICL performance and more surprising pruning weights in deep layers often results in more stable performance improvements in shallow layers. However the underlying mechanism of those findings still remains an open question. To reveal those findings we conduct an in45;depth theoretical analysis by presenting the implicit gradient descent (GD) trajectories of ICL and giving the mutual information based generalization bounds of ICL via full implicit GD trajectories. This helps us reasonably explain the surprising experimental findings. Besides based on all our experimental and theoretical insights we intuitively propose a simple model45;compression and derivative45;free algorithm for downstream tasks in enhancing ICL inference. Experiments on benchmark datasets and open source LLMs display the method effectivenessfootnote123;The code is available at url123;https://github.com/chen123CtrlS/EnhancingICL&#95;SVDPruning&#125;&#125;.
