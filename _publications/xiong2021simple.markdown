---
layout: publication
title: Simple Local Attentions Remain Competitive For Long45;context Tasks
authors: Xiong Wenhan, Oğuz Barlas, Gupta Anchit, Chen Xilun, Liskovich Diana, Levy Omer, Yih Wen-tau, Mehdad Yashar
conference: "Arxiv"
year: 2021
bibkey: xiong2021simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.07210"}
  - {name: "Code", url: "https://github.com/pytorch/fairseq/tree/main/examples/xformers"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Many NLP tasks require processing long contexts beyond the length limit of pretrained models. In order to scale these models to longer text sequences many efficient long45;range attention variants have been proposed. Despite the abundance of research along this direction it is still difficult to gauge the relative effectiveness of these models in practical use cases e.g. if we apply these models following the pretrain45;and45;finetune paradigm. In this work we aim to conduct a thorough analysis of these emerging models with large45;scale and controlled experiments. For each attention variant we pretrain large45;size models using the same long45;doc corpus and then finetune these models for real45;world long45;context tasks. Our findings reveal pitfalls of an existing widely45;used long45;range benchmark and show none of the tested efficient attentions can beat a simple local window attention under standard pretraining paradigms. Further analysis on local attention variants suggests that even the commonly used attention45;window overlap is not necessary to achieve good downstream results 45;45; using disjoint local attentions we are able to build a simpler and more efficient long45;doc QA model that matches the performance of Longformer~citep123;longformer125; with half of its pretraining compute. The code to replicate our experiments can be found at https://github.com/pytorch/fairseq/tree/main/examples/xformers
