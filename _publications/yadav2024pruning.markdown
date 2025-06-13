---
layout: publication
title: 'Pruning Literals For Highly Efficient Explainability At Word Level'
authors: Rohan Kumar Yadav, Bimal Bhattarai, Abhik Jana, Lei Jiao, Seid Muhie Yimam
conference: "2024 International Symposium on the Tsetlin Machine (ISTM)"
year: 2024
bibkey: yadav2024pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.04557"}
tags: ['Efficiency and Optimization', 'Interpretability and Explainability', 'Pruning', 'Model Architecture', 'Interpretability', 'Attention Mechanism']
---
Designing an explainable model becomes crucial now for Natural Language
Processing(NLP) since most of the state-of-the-art machine learning models
provide a limited explanation for the prediction. In the spectrum of an
explainable model, Tsetlin Machine(TM) is promising because of its capability
of providing word-level explanation using proposition logic. However, concern
rises over the elaborated combination of literals (propositional logic) in the
clause that makes the model difficult for humans to comprehend, despite having
a transparent learning process. In this paper, we design a post-hoc pruning of
clauses that eliminate the randomly placed literals in the clause thereby
making the model more efficiently interpretable than the vanilla TM.
Experiments on the publicly available YELP-HAT Dataset demonstrate that the
proposed pruned TM's attention map aligns more with the human attention map
than the vanilla TM's attention map. In addition, the pairwise similarity
measure also surpasses the attention map-based neural network models. In terms
of accuracy, the proposed pruning method does not degrade the accuracy
significantly but rather enhances the performance up to 4% to 9% in some test
data.
