---
layout: publication
title: Zero45;shot Recommendation As Language Modeling
authors: Damien Sileo, Wout Vossen, Robbe Raymaekers
conference: "Arxiv"
year: 2021
bibkey: sileo2021zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2112.04184v1"}
  - {name: "Code", url: "https://colab.research.google.com/drive/1f1mlZ&#45;FGaLGdo5rPzxf3vemKllbh2esT?usp=sharing)"}
tags: ['Has Code', 'Language Modeling', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Recommendation is the task of ranking items (e.g. movies or products) according to individual user needs. Current systems rely on collaborative filtering and content45;based techniques which both require structured training data. We propose a framework for recommendation with off45;the45;shelf pretrained language models (LM) that only used unstructured text corpora as training data. If a user u liked textit123;Matrix125; and textit123;Inception125; we construct a textual prompt e.g. textit123;Movies like Matrix Inception 123;<125;m123;125;125; to estimate the affinity between u and m with LM likelihood. We motivate our idea with a corpus analysis evaluate several prompt structures and we compare LM45;based recommendation with standard matrix factorization trained on different data regimes. The code for our experiments is publicly available (https://colab.research.google.com/drive/1f1mlZ&#45;FGaLGdo5rPzxf3vemKllbh2esT?usp=sharing).
