---
layout: publication
title: 'Camembert: Cascading Assistant-mediated Multilingual BERT'
authors: Dan Degenaro, Jugal Kalita
conference: "Arxiv"
year: 2022
bibkey: degenaro2022cascading
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2212.11456'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'BERT', 'Fine-Tuning', 'Pretraining Methods']
---
Large language models having hundreds of millions, and even billions, of
parameters have performed extremely well on a variety of natural language
processing (NLP) tasks. Their widespread use and adoption, however, is hindered
by the lack of availability and portability of sufficiently large computational
resources. This paper proposes a knowledge distillation (KD) technique building
on the work of LightMBERT, a student model of multilingual BERT (mBERT). By
repeatedly distilling mBERT through increasingly compressed toplayer distilled
teacher assistant networks, CAMeMBERT aims to improve upon the time and space
complexities of mBERT while keeping loss of accuracy beneath an acceptable
threshold. At present, CAMeMBERT has an average accuracy of around 60.1%, which
is subject to change after future improvements to the hyperparameters used in
fine-tuning.
