---
layout: publication
title: 'Continual Pre-training Mitigates Forgetting In Language And Vision'
authors: Andrea Cossu, Tinne Tuytelaars, Antonio Carta, Lucia Passaro, Vincenzo Lomonaco, Davide Bacciu
conference: "Arxiv"
year: 2022
bibkey: cossu2022continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.09357"}
  - {name: "Code", url: "https://github.com/AndreaCossu/continual-pretraining-nlp-vision"}
tags: ['Pre-Training', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Pre-trained models are nowadays a fundamental component of machine learning
research. In continual learning, they are commonly used to initialize the model
before training on the stream of non-stationary data. However, pre-training is
rarely applied during continual learning. We formalize and investigate the
characteristics of the continual pre-training scenario in both language and
vision environments, where a model is continually pre-trained on a stream of
incoming data and only later fine-tuned to different downstream tasks. We show
that continually pre-trained models are robust against catastrophic forgetting
and we provide strong empirical evidence supporting the fact that
self-supervised pre-training is more effective in retaining previous knowledge
than supervised protocols. Code is provided at
https://github.com/AndreaCossu/continual-pretraining-nlp-vision .
