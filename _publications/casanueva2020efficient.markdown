---
layout: publication
title: Efficient Intent Detection With Dual Sentence Encoders
authors: "I\xF1igo Casanueva, Tadas Tem\u010Dinas, Daniela Gerz, Matthew Henderson,\
  \ Ivan Vuli\u0107"
conference: Arxiv
year: 2020
citations: 105
bibkey: casanueva2020efficient
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.04807'}]
tags: [Few-Shot, Fine-Tuning, BERT]
---
Building conversational systems in new domains and with added functionality
requires resource-efficient models that work under low-data regimes (i.e., in
few-shot setups). Motivated by these requirements, we introduce intent
detection methods backed by pretrained dual sentence encoders such as USE and
ConveRT. We demonstrate the usefulness and wide applicability of the proposed
intent detectors, showing that: 1) they outperform intent detectors based on
fine-tuning the full BERT-Large model or using BERT as a fixed black-box
encoder on three diverse intent detection data sets; 2) the gains are
especially pronounced in few-shot setups (i.e., with only 10 or 30 annotated
examples per intent); 3) our intent detectors can be trained in a matter of
minutes on a single CPU; and 4) they are stable across different hyperparameter
settings. In hope of facilitating and democratizing research focused on
intention detection, we release our code, as well as a new challenging
single-domain intent detection dataset comprising 13,083 annotated examples
over 77 intents.