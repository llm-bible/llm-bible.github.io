---
layout: publication
title: 'Simple Local Attentions Remain Competitive For Long-context Tasks'
authors: Xiong Wenhan, Oğuz Barlas, Gupta Anchit, Chen Xilun, Liskovich Diana, Levy Omer, Yih Wen-tau, Mehdad Yashar
conference: "Arxiv"
year: 2021
bibkey: xiong2021simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.07210"}
  - {name: "Code", url: "https://github.com/pytorch/fairseq/tree/main/examples/xformers"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
'Many NLP tasks require processing long contexts beyond the length limit of pretrained models. In order to scale these models to longer text sequences, many efficient long-range attention variants have been proposed. Despite the abundance of research along this direction, it is still difficult to gauge the relative effectiveness of these models in practical use cases, e.g., if we apply these models following the pretrain-and-finetune paradigm. In this work, we aim to conduct a thorough analysis of these emerging models with large-scale and controlled experiments. For each attention variant, we pretrain large-size models using the same long-doc corpus and then finetune these models for real-world long-context tasks. Our findings reveal pitfalls of an existing widely-used long-range benchmark and show none of the tested efficient attentions can beat a simple local window attention under standard pretraining paradigms. Further analysis on local attention variants suggests that even the commonly used attention-window overlap is not necessary to achieve good downstream results -- using disjoint local attentions, we are able to build a simpler and more efficient long-doc QA model that matches the performance of Longformer~\citep\{longformer\} with half of its pretraining compute. The code to replicate our experiments can be found at https://github.com/pytorch/fairseq/tree/main/examples/xformers'
