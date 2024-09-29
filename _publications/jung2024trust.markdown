---
layout: publication
title: Trust Or Escalate LLM Judges With Provable Guarantees For Human Agreement
authors: Jung Jaehun, Brahman Faeze, Choi Yejin
conference: "Arxiv"
year: 2024
bibkey: jung2024trust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18370"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'RAG', 'Tools']
---
We present a principled approach to provide LLM45;based evaluation with a rigorous guarantee of human agreement. We first propose that a reliable evaluation method should not uncritically rely on model preferences for pairwise evaluation but rather assess the confidence of judge models and selectively decide when to trust its judgement. We then show that under this selective evaluation framework human agreement can be provably guaranteed 45;45; such that the model evaluation aligns with that of humans to a user45;specified agreement level. As part of our framework we also introduce Simulated Annotators a novel confidence estimation method that significantly improves judge calibration and thus enables high coverage of evaluated instances. Finally we propose Cascaded Selective Evaluation where we use cheaper models as initial judges and escalate to stronger models only when necessary 45;45; again while still providing a provable guarantee of human agreement. Experimental results show that Cascaded Selective Evaluation guarantees strong alignment with humans far beyond what LLM judges could achieve without selective evaluation. For example on a subset of Chatbot Arena where GPT45;4 almost never achieves 8037; human agreement our method even while employing substantially cost45;effective models such as Mistral45;7B guarantees over 8037; human agreement with almost 8037; test coverage.
