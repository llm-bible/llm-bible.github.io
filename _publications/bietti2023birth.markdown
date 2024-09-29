---
layout: publication
title: Birth Of A Transformer A Memory Viewpoint
authors: Bietti Alberto, Cabannes Vivien, Bouchacourt Diane, Jegou Herve, Bottou Leon
conference: "Arxiv"
year: 2023
bibkey: bietti2023birth
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.00802"}
tags: ['Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Large language models based on transformers have achieved great empirical successes. However as they are deployed more widely there is a growing need to better understand their internal mechanisms in order to make them more reliable. These models appear to store vast amounts of knowledge from their training data and to adapt quickly to new information provided in their context or prompt. We study how transformers balance these two types of knowledge by considering a synthetic setup where tokens are generated from either global or context45;specific bigram distributions. By a careful empirical analysis of the training process on a simplified two45;layer transformer we illustrate the fast learning of global bigrams and the slower development of an induction head mechanism for the in45;context bigrams. We highlight the role of weight matrices as associative memories provide theoretical insights on how gradients enable their learning during training and study the role of data45;distributional properties.
