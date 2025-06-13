---
layout: publication
title: 'Improving Transformers With Probabilistic Attention Keys'
authors: Tam Nguyen, Tan M. Nguyen, Dung D. Le, Duy Khuong Nguyen, Viet-anh Tran, Richard G. Baraniuk, Nhat Ho, Stanley J. Osher
conference: "Proceedings of the 39th International Conference on Machine Learning Baltimore Maryland USA PMLR 162 2022"
year: 2021
bibkey: nguyen2021improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08678"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
Multi-head attention is a driving force behind state-of-the-art transformers,
which achieve remarkable performance across a variety of natural language
processing (NLP) and computer vision tasks. It has been observed that for many
applications, those attention heads learn redundant embedding, and most of them
can be removed without degrading the performance of the model. Inspired by this
observation, we propose Transformer with a Mixture of Gaussian Keys
(Transformer-MGK), a novel transformer architecture that replaces redundant
heads in transformers with a mixture of keys at each head. These mixtures of
keys follow a Gaussian mixture model and allow each attention head to focus on
different parts of the input sequence efficiently. Compared to its conventional
transformer counterpart, Transformer-MGK accelerates training and inference,
has fewer parameters, and requires fewer FLOPs to compute while achieving
comparable or better accuracy across tasks. Transformer-MGK can also be easily
extended to use with linear attention. We empirically demonstrate the advantage
of Transformer-MGK in a range of practical applications, including language
modeling and tasks that involve very long sequences. On the Wikitext-103 and
Long Range Arena benchmark, Transformer-MGKs with 4 heads attain comparable or
better performance to the baseline transformers with 8 heads.
