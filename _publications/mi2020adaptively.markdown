---
layout: publication
title: 'ADER: Adaptively Distilled Exemplar Replay Towards Continual Learning For Session-based Recommendation'
authors: Fei Mi, Xiaoyu Lin, Boi Faltings
conference: "Arxiv"
year: 2020
bibkey: mi2020adaptively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2007.12000"}
tags: ['Efficiency and Optimization', 'Applications', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Distillation']
---
Session-based recommendation has received growing attention recently due to
the increasing privacy concern. Despite the recent success of neural
session-based recommenders, they are typically developed in an offline manner
using a static dataset. However, recommendation requires continual adaptation
to take into account new and obsolete items and users, and requires "continual
learning" in real-life applications. In this case, the recommender is updated
continually and periodically with new data that arrives in each update cycle,
and the updated model needs to provide recommendations for user activities
before the next model update. A major challenge for continual learning with
neural models is catastrophic forgetting, in which a continually trained model
forgets user preference patterns it has learned before. To deal with this
challenge, we propose a method called Adaptively Distilled Exemplar Replay
(ADER) by periodically replaying previous training samples (i.e., exemplars) to
the current model with an adaptive distillation loss. Experiments are conducted
based on the state-of-the-art SASRec model using two widely used datasets to
benchmark ADER with several well-known continual learning techniques. We
empirically demonstrate that ADER consistently outperforms other baselines, and
it even outperforms the method using all historical data at every update cycle.
This result reveals that ADER is a promising solution to mitigate the
catastrophic forgetting issue towards building more realistic and scalable
session-based recommenders.
