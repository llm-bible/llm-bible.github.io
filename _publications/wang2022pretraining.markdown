---
layout: publication
title: 'Pretraining Without Attention'
authors: Wang Junxiong, Yan Jing Nathan, Gu Albert, Rush Alexander M.
conference: "Arxiv"
year: 2022
bibkey: wang2022pretraining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10544"}
  - {name: "Code", url: "https://github.com/jxiw/BiGS"}
tags: ['Attention Mechanism', 'BERT', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Transformers have been essential to pretraining success in NLP. While other architectures have been used downstream accuracy is either significantly worse or requires attention layers to match standard benchmarks such as GLUE. This work explores pretraining without attention by using recent advances in sequence routing based on state-space models (SSMs). Our proposed model Bidirectional Gated SSM (BiGS) combines SSM layers with a multiplicative gating architecture that has been effective in simplified sequence modeling architectures. The model learns static layers that do not consider pair-wise interactions. Even so BiGS is able to match BERT pretraining accuracy on GLUE and can be extended to long-form pretraining of 4096 tokens without approximation. Analysis shows that while the models have similar average accuracy the approach has different inductive biases than BERT in terms of interactions and syntactic representations. All models from this work are available at https://github.com/jxiw/BiGS."
