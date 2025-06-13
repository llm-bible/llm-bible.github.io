---
layout: publication
title: 'Self-guided Curriculum Learning For Neural Machine Translation'
authors: Lei Zhou, Liang Ding, Kevin Duh, Shinji Watanabe, Ryohei Sasano, Koichi Takeda
conference: "Arxiv"
year: 2021
bibkey: zhou2021self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.04475"}
tags: ['Transformer', 'Applications', 'RAG', 'Model Architecture', 'WMT', 'Training Techniques', 'Pretraining Methods']
---
In the field of machine learning, the well-trained model is assumed to be
able to recover the training labels, i.e. the synthetic labels predicted by the
model should be as close to the ground-truth labels as possible. Inspired by
this, we propose a self-guided curriculum strategy to encourage the learning of
neural machine translation (NMT) models to follow the above recovery criterion,
where we cast the recovery degree of each training example as its learning
difficulty. Specifically, we adopt the sentence level BLEU score as the proxy
of recovery degree. Different from existing curricula relying on linguistic
prior knowledge or third-party language models, our chosen learning difficulty
is more suitable to measure the degree of knowledge mastery of the NMT models.
Experiments on translation benchmarks, including WMT14
English\\(\Rightarrow\\)German and WMT17 Chinese\\(\Rightarrow\\)English, demonstrate
that our approach can consistently improve translation performance against
strong baseline Transformer.
