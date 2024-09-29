---
layout: publication
title: Towards Trustworthy Deception Detection Benchmarking Model Robustness across Domains Modalities and Languages
authors: Glenski Maria, Ayton Ellyn, Cosbey Robin, Arendt Dustin, Volkova Svitlana
conference: "Proceedings of the"
year: 2021
bibkey: glenski2021towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.11761"}
tags: ['BERT', 'Merging', 'Model Architecture', 'Multimodal Models', 'Security', 'Tools', 'Training Techniques']
---
Evaluating model robustness is critical when developing trustworthy models not only to gain deeper understanding of model behavior strengths and weaknesses but also to develop future models that are generalizable and robust across expected environments a model may encounter in deployment. In this paper we present a framework for measuring model robustness for an important but difficult text classification task - deceptive news detection. We evaluate model robustness to out-of-domain data modality-specific features and languages other than English. Our investigation focuses on three type of models LSTM models trained on multiple datasets(Cross-Domain) several fusion LSTM models trained with images and text and evaluated with three state-of-the-art embeddings BERT ELMo and GloVe (Cross-Modality) and character-level CNN models trained on multiple languages (Cross-Language). Our analyses reveal a significant drop in performance when testing neural models on out-of-domain data and non-English languages that may be mitigated using diverse training data. We find that with additional image content as input ELMo embeddings yield significantly fewer errors compared to BERT orGLoVe. Most importantly this work not only carefully analyzes deception model robustness but also provides a framework of these analyses that can be applied to new models or extended datasets in the future.
