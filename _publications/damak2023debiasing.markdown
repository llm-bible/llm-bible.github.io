---
layout: publication
title: 'Debiasing The Cloze Task In Sequential Recommendation With Bidirectional Transformers'
authors: Khalil Damak, Sami Khenissi, Olfa Nasraoui
conference: "Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 22) August 14-18 2022 Washington DC USA"
year: 2023
bibkey: damak2023debiasing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.09210"}
tags: ['Transformer', 'Ethics and Bias', 'Language Modeling', 'Model Architecture', 'Security', 'Masked Language Model', 'Pretraining Methods', 'BERT']
---
Bidirectional Transformer architectures are state-of-the-art sequential
recommendation models that use a bi-directional representation capacity based
on the Cloze task, a.k.a. Masked Language Modeling. The latter aims to predict
randomly masked items within the sequence. Because they assume that the true
interacted item is the most relevant one, an exposure bias results, where
non-interacted items with low exposure propensities are assumed to be
irrelevant. The most common approach to mitigating exposure bias in
recommendation has been Inverse Propensity Scoring (IPS), which consists of
down-weighting the interacted predictions in the loss function in proportion to
their propensities of exposure, yielding a theoretically unbiased learning. In
this work, we argue and prove that IPS does not extend to sequential
recommendation because it fails to account for the temporal nature of the
problem. We then propose a novel propensity scoring mechanism, which can
theoretically debias the Cloze task in sequential recommendation. Finally we
empirically demonstrate the debiasing capabilities of our proposed approach and
its robustness to the severity of exposure bias.
