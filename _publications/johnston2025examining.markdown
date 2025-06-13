---
layout: publication
title: 'Examining Two Hop Reasoning Through Information Content Scaling'
authors: David Johnston, Nora Belrose
conference: "Arxiv"
year: 2025
bibkey: johnston2025examining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03490"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Interpretability and Explainability']
---
Prior work has found that transformers have an inconsistent ability to learn
to answer latent two-hop questions -- questions of the form "Who is Bob's
mother's boss?" We study why this is the case by examining how transformers'
capacity to learn datasets of two-hop questions and answers (two-hop QA) scales
with their size, motivated by prior work on transformer knowledge capacity for
simple factual memorization. We find that capacity scaling and generalization
both support the hypothesis that latent two-hop QA requires transformers to
learn each fact twice, while two-hop QA with chain of thought does not. We also
show that with appropriate dataset parameters, it is possible to "trap" very
small models in a regime where they memorize answers to two-hop questions
independently, even though they would perform better if they could learn to
answer them with function composition. Our findings show that measurement of
capacity scaling can complement existing interpretability methods, though there
are challenges in using it for this purpose.
