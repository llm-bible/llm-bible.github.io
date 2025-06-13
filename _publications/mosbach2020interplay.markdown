---
layout: publication
title: 'On The Interplay Between Fine-tuning And Sentence-level Probing For Linguistic Knowledge In Pre-trained Transformers'
authors: Marius Mosbach, Anna Khokhlova, Michael A. Hedderich, Dietrich Klakow
conference: "Arxiv"
year: 2020
bibkey: mosbach2020interplay
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.02616"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'BERT', 'Transformer', 'Fine-Tuning']
---
Fine-tuning pre-trained contextualized embedding models has become an
integral part of the NLP pipeline. At the same time, probing has emerged as a
way to investigate the linguistic knowledge captured by pre-trained models.
Very little is, however, understood about how fine-tuning affects the
representations of pre-trained models and thereby the linguistic knowledge they
encode. This paper contributes towards closing this gap. We study three
different pre-trained models: BERT, RoBERTa, and ALBERT, and investigate
through sentence-level probing how fine-tuning affects their representations.
We find that for some probing tasks fine-tuning leads to substantial changes in
accuracy, possibly suggesting that fine-tuning introduces or even removes
linguistic knowledge from a pre-trained model. These changes, however, vary
greatly across different models, fine-tuning and probing tasks. Our analysis
reveals that while fine-tuning indeed changes the representations of a
pre-trained model and these changes are typically larger for higher layers,
only in very few cases, fine-tuning has a positive effect on probing accuracy
that is larger than just using the pre-trained model with a strong pooling
method. Based on our findings, we argue that both positive and negative effects
of fine-tuning on probing require a careful interpretation.
