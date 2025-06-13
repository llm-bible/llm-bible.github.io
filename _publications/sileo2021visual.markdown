---
layout: publication
title: 'Visual Grounding Strategies For Text-only Natural Language Processing'
authors: Damien Sileo
conference: "Arxiv"
year: 2021
bibkey: sileo2021visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.13942"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Language Modeling', 'RAG', 'Pretraining Methods', 'BERT']
---
Visual grounding is a promising path toward more robust and accurate Natural
Language Processing (NLP) models. Many multimodal extensions of BERT (e.g.,
VideoBERT, LXMERT, VL-BERT) allow a joint modeling of texts and images that
lead to state-of-the-art results on multimodal tasks such as Visual Question
Answering. Here, we leverage multimodal modeling for purely textual tasks
(language modeling and classification) with the expectation that the multimodal
pretraining provides a grounding that can improve text processing accuracy. We
propose possible strategies in this respect. A first type of strategy, referred
to as \{\it transferred grounding\} consists in applying multimodal models to
text-only tasks using a placeholder to replace image input. The second one,
which we call \{\it associative grounding\}, harnesses image retrieval to match
texts with related images during both pretraining and text-only downstream
tasks. We draw further distinctions into both strategies and then compare them
according to their impact on language modeling and commonsense-related
downstream tasks, showing improvement over text-only baselines.
