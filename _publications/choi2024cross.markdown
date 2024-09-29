---
layout: publication
title: Cross-architecture Transfer Learning For Linear-cost Inference Transformers
authors: Choi Sehyun
conference: "Arxiv"
year: 2024
bibkey: choi2024cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02684"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Recently multiple architectures has been proposed to improve the efficiency of the Transformer Language Models through changing the design of the self-attention block to have a linear-cost inference (LCI). A notable approach in this realm is the State-Space Machines (SSMs) architecture which showed on-par performance on language modeling tasks with the self-attention transformers. However such an architectural change requires a full pretraining of the weights from scratch which incurs a huge cost to researchers and practitioners who want to use the new architectures. In the more traditional linear attention works it has been proposed to approximate full attention with linear attention by swap-and-finetune framework. Motivated by this approach we propose Cross-Architecture Transfer Learning (XATL) in which the weights of the shared components between LCI and self-attention-based transformers such as layernorms MLPs input/output embeddings are directly transferred to the new architecture from already pre-trained model parameters. We experimented the efficacy of the method on varying sizes and alternative attention architectures and show that (methodabbr) significantly reduces the training time up to 2.5x times and converges to a better minimum with up to 2.637; stronger model on the LM benchmarks within the same compute budget.
