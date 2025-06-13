---
layout: publication
title: 'Language Model Pre-training With Sparse Latent Typing'
authors: Liliang Ren, Zixuan Zhang, Han Wang, Clare R. Voss, Chengxiang Zhai, Heng Ji
conference: "Arxiv"
year: 2022
bibkey: ren2022language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.12582"}
  - {name: "Code", url: "https://github.com/renll/SparseLT"}
tags: ['Training Techniques', 'Few-Shot', 'Pre-Training', 'Has Code']
---
Modern large-scale Pre-trained Language Models (PLMs) have achieved
tremendous success on a wide range of downstream tasks. However, most of the LM
pre-training objectives only focus on text reconstruction, but have not sought
to learn latent-level interpretable representations of sentences. In this
paper, we manage to push the language models to obtain a deeper understanding
of sentences by proposing a new pre-training objective, Sparse Latent Typing,
which enables the model to sparsely extract sentence-level keywords with
diverse latent types. Experimental results show that our model is able to learn
interpretable latent type categories in a self-supervised manner without using
any external knowledge. Besides, the language model pre-trained with such an
objective also significantly improves Information Extraction related downstream
tasks in both supervised and few-shot settings. Our code is publicly available
at: https://github.com/renll/SparseLT.
