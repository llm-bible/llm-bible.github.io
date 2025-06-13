---
layout: publication
title: 'Tuning Language Models By Mixture-of-depths Ensemble'
authors: Haoyan Luo, Lucia Specia
conference: "Arxiv"
year: 2024
bibkey: luo2024tuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13077"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
Transformer-based Large Language Models (LLMs) traditionally rely on
final-layer loss for training and final-layer representations for predictions,
potentially overlooking the predictive power embedded in intermediate layers.
Surprisingly, we find that focusing training efforts on these intermediate
layers can yield training losses comparable to those of final layers, with
complementary test-time performance. We introduce a novel tuning framework,
Mixture-of-Depths (MoD), which trains late layers as ensembles contributing to
the final logits through learned routing weights. With the auxiliary
distillation loss and additional normalization modules, we ensure that the
outputs of the late layers adapt to language modeling. Our MoD framework, which
can be integrated with any existing tuning method, shows consistent improvement
on various language modelling tasks. Furthermore, by replacing traditional
trainable modules with MoD, our approach achieves similar performance with
significantly fewer trainable parameters, demonstrating the potential of
leveraging predictive power from intermediate representations during training.
