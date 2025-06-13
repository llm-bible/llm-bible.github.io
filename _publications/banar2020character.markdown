---
layout: publication
title: 'Character-level Transformer-based Neural Machine Translation'
authors: Nikolay Banar, Walter Daelemans, Mike Kestemont
conference: "Arxiv"
year: 2020
bibkey: banar2020character
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2005.11239'}
tags: ['Transformer', 'WMT', 'Training Techniques', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Neural machine translation (NMT) is nowadays commonly applied at the subword
level, using byte-pair encoding. A promising alternative approach focuses on
character-level translation, which simplifies processing pipelines in NMT
considerably. This approach, however, must consider relatively longer
sequences, rendering the training process prohibitively expensive. In this
paper, we discuss a novel, Transformer-based approach, that we compare, both in
speed and in quality to the Transformer at subword and character levels, as
well as previously developed character-level models. We evaluate our models on
4 language pairs from WMT'15: DE-EN, CS-EN, FI-EN and RU-EN. The proposed novel
architecture can be trained on a single GPU and is 34% percent faster than the
character-level Transformer; still, the obtained results are at least on par
with it. In addition, our proposed model outperforms the subword-level model in
FI-EN and shows close results in CS-EN. To stimulate further research in this
area and close the gap with subword-level NMT, we make all our code and models
publicly available.
