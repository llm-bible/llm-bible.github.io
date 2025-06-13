---
layout: publication
title: 'Large Language Models For Expansion Of Spoken Language Understanding Systems To New Languages'
authors: Jakub Hoscilowicz, Pawel Pawlowski, Marcin Skorupa, Marcin Sowański, Artur Janicki
conference: "Arxiv"
year: 2024
bibkey: hoscilowicz2024large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.02588'}
tags: ['Training Techniques', 'BERT', 'Tools', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Spoken Language Understanding (SLU) models are a core component of voice
assistants (VA), such as Alexa, Bixby, and Google Assistant. In this paper, we
introduce a pipeline designed to extend SLU systems to new languages, utilizing
Large Language Models (LLMs) that we fine-tune for machine translation of
slot-annotated SLU training data. Our approach improved on the MultiATIS++
benchmark, a primary multi-language SLU dataset, in the cloud scenario using an
mBERT model. Specifically, we saw an improvement in the Overall Accuracy
metric: from 53% to 62.18%, compared to the existing state-of-the-art method,
Fine and Coarse-grained Multi-Task Learning Framework (FC-MTLF). In the
on-device scenario (tiny and not pretrained SLU), our method improved the
Overall Accuracy from 5.31% to 22.06% over the baseline Global-Local
Contrastive Learning Framework (GL-CLeF) method. Contrary to both FC-MTLF and
GL-CLeF, our LLM-based machine translation does not require changes in the
production architecture of SLU. Additionally, our pipeline is slot-type
independent: it does not require any slot definitions or examples.
