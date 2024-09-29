---
layout: publication
title: Can Transformer Models Measure Coherence In Text Re45;thinking The Shuffle Test
authors: Laban Philippe, Dai Luke, Bandarkar Lucas, Hearst Marti A.
conference: "Association for Computational Linguistics"
year: 2021
bibkey: laban2021can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.03448"}
  - {name: "Code", url: "https://github.com/tingofurro/shuffle&#95;test/"}
tags: ['BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
The Shuffle Test is the most common task to evaluate whether NLP models can measure coherence in text. Most recent work uses direct supervision on the task; we show that by simply finetuning a RoBERTa model we can achieve a near perfect accuracy of 97.837; a state45;of45;the45;art. We argue that this outstanding performance is unlikely to lead to a good model of text coherence and suggest that the Shuffle Test should be approached in a Zero45;Shot setting models should be evaluated without being trained on the task itself. We evaluate common models in this setting such as Generative and Bi45;directional Transformers and find that larger architectures achieve high45;performance out45;of45;the45;box. Finally we suggest the k45;Block Shuffle Test a modification of the original by increasing the size of blocks shuffled. Even though human reader performance remains high (around 9537; accuracy) model performance drops from 9437; to 7837; as block size increases creating a conceptually simple challenge to benchmark NLP models. Code available https://github.com/tingofurro/shuffle&#95;test/
