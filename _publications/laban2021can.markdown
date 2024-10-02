---
layout: publication
title: 'Can Transformer Models Measure Coherence In Text? Re-thinking The Shuffle Test'
authors: Laban Philippe, Dai Luke, Bandarkar Lucas, Hearst Marti A.
conference: "Association for Computational Linguistics"
year: 2021
bibkey: laban2021can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.03448"}
  - {name: "Code", url: "https://github.com/tingofurro/shuffle_test/"}
tags: ['BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
'The Shuffle Test is the most common task to evaluate whether NLP models can measure coherence in text. Most recent work uses direct supervision on the task; we show that by simply finetuning a RoBERTa model, we can achieve a near perfect accuracy of 97.8&#37;, a state-of-the-art. We argue that this outstanding performance is unlikely to lead to a good model of text coherence, and suggest that the Shuffle Test should be approached in a Zero-Shot setting: models should be evaluated without being trained on the task itself. We evaluate common models in this setting, such as Generative and Bi-directional Transformers, and find that larger architectures achieve high-performance out-of-the-box. Finally, we suggest the k-Block Shuffle Test, a modification of the original by increasing the size of blocks shuffled. Even though human reader performance remains high (around 95&#37; accuracy), model performance drops from 94&#37; to 78&#37; as block size increases, creating a conceptually simple challenge to benchmark NLP models. Code available: https://github.com/tingofurro/shuffle\_test/'
