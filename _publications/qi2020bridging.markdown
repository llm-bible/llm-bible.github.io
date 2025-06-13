---
layout: publication
title: 'BANG: Bridging Autoregressive And Non-autoregressive Generation With Large Scale Pretraining'
authors: Weizhen Qi, Yeyun Gong, Jian Jiao, Yu Yan, Weizhu Chen, Dayiheng Liu, Kewen Tang, Houqiang Li, Jiusheng Chen, Ruofei Zhang, Ming Zhou, Nan Duan
conference: "Arxiv"
year: 2020
bibkey: qi2020bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.15525"}
tags: ['GPT', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
In this paper, we propose BANG, a new pretraining model to Bridge the gap
between Autoregressive (AR) and Non-autoregressive (NAR) Generation. AR and NAR
generation can be uniformly regarded as to what extent previous tokens can be
attended, and BANG bridges AR and NAR generation by designing a novel model
structure for large-scale pretraining. The pretrained BANG model can
simultaneously support AR, NAR and semi-NAR generation to meet different
requirements. Experiments on question generation (SQuAD 1.1), summarization
(XSum) and dialogue generation (PersonaChat) show that BANG improves NAR and
semi-NAR performance significantly as well as attaining comparable performance
with strong AR pretrained models. Compared with the semi-NAR strong baselines,
BANG achieves absolute improvements of 14.01 and 5.24 in the overall scores of
SQuAD 1.1 and XSum, respectively. In addition, BANG achieves absolute
improvements of 10.73, 6.39 and 5.90 in the overall scores of SQuAD, XSUM and
PersonaChat respectively compared with the strong NAR baselines.
