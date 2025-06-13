---
layout: publication
title: 'Pre-trained Language Models For Keyphrase Generation: A Thorough Empirical Study'
authors: Di Wu, Wasi Uddin Ahmad, Kai-wei Chang
conference: "Arxiv"
year: 2022
bibkey: wu2022pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10233"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'BERT', 'Pre-Training']
---
Neural models that do not rely on pre-training have excelled in the keyphrase
generation task with large annotated datasets. Meanwhile, new approaches have
incorporated pre-trained language models (PLMs) for their data efficiency.
However, there lacks a systematic study of how the two types of approaches
compare and how different design choices can affect the performance of
PLM-based models. To fill in this knowledge gap and facilitate a more informed
use of PLMs for keyphrase extraction and keyphrase generation, we present an
in-depth empirical study. Formulating keyphrase extraction as sequence labeling
and keyphrase generation as sequence-to-sequence generation, we perform
extensive experiments in three domains. After showing that PLMs have
competitive high-resource performance and state-of-the-art low-resource
performance, we investigate important design choices including in-domain PLMs,
PLMs with different pre-training objectives, using PLMs with a parameter
budget, and different formulations for present keyphrases. Further results show
that (1) in-domain BERT-like PLMs can be used to build strong and
data-efficient keyphrase generation models; (2) with a fixed parameter budget,
prioritizing model depth over width and allocating more layers in the encoder
leads to better encoder-decoder models; and (3) introducing four in-domain
PLMs, we achieve a competitive performance in the news domain and the
state-of-the-art performance in the scientific domain.
