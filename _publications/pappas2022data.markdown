---
layout: publication
title: 'Data Augmentation For Biomedical Factoid Question Answering'
authors: Dimitris Pappas, Prodromos Malakasiotis, Ion Androutsopoulos
conference: "Arxiv"
year: 2022
bibkey: pappas2022data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.04711"}
tags: ['Transformer', 'Applications', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Masked Language Model', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
We study the effect of seven data augmentation (da) methods in factoid
question answering, focusing on the biomedical domain, where obtaining training
instances is particularly difficult. We experiment with data from the BioASQ
challenge, which we augment with training instances obtained from an artificial
biomedical machine reading comprehension dataset, or via back-translation,
information retrieval, word substitution based on word2vec embeddings, or
masked language modeling, question generation, or extending the given passage
with additional context. We show that da can lead to very significant
performance gains, even when using large pre-trained Transformers, contributing
to a broader discussion of if/when da benefits large pre-trained models. One of
the simplest da methods, word2vec-based word substitution, performed best and
is recommended. We release our artificial training instances and code.
