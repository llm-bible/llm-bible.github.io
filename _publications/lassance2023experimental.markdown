---
layout: publication
title: 'An Experimental Study On Pretraining Transformers From Scratch For IR'
authors: Lassance Carlos, Déjean Hervé, Clinchant Stéphane
conference: "Arxiv"
year: 2023
bibkey: lassance2023experimental
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.10444"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Finetuning Pretrained Language Models (PLM) for IR has been de facto the standard practice since their breakthrough effectiveness few years ago. But, is this approach well understood? In this paper, we study the impact of the pretraining collection on the final IR effectiveness. In particular, we challenge the current hypothesis that PLM shall be trained on a large enough generic collection and we show that pretraining from scratch on the collection of interest is surprisingly competitive with the current approach. We benchmark first-stage ranking rankers and cross-encoders for reranking on the task of general passage retrieval on MSMARCO, Mr-Tydi for Arabic, Japanese and Russian, and TripClick for specific domain. Contrary to popular belief, we show that, for finetuning first-stage rankers, models pretrained solely on their collection have equivalent or better effectiveness compared to more general models. However, there is a slight effectiveness drop for rerankers pretrained only on the target collection. Overall, our study sheds a new light on the role of the pretraining collection and should make our community ponder on building specialized models by pretraining from scratch. Last but not least, doing so could enable better control of efficiency, data bias and replicability, which are key research questions for the IR community.
