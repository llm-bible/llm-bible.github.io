---
layout: publication
title: 'Harnessing The Power Of Multi-task Pretraining For Ground-truth Level Natural Language Explanations'
authors: Plüster Björn, Ambsdorf Jakob, Braach Lukas, Lee Jae Hee, Wermter Stefan
conference: "Arxiv"
year: 2022
bibkey: plüster2022harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.04231"}
tags: ['Ethics And Bias', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Natural language explanations promise to offer intuitively understandable explanations of a neural networks decision process in complex vision-language tasks as pursued in recent VL-NLE models. While current models offer impressive performance on task accuracy and explanation plausibility they suffer from a range of issues Some models feature a modular design where the explanation generation module is poorly integrated with a separate module for task-answer prediction employ backbone models trained on limited sets of tasks or incorporate ad hoc solutions to increase performance on single datasets. We propose to evade these limitations by applying recent advances in large-scale multi-task pretraining of generative Transformer models to the problem of VL-NLE tasks. Our approach outperforms recent models by a large margin with human annotators preferring the generated explanations over the ground truth in two out of three evaluated datasets. As a novel challenge in VL-NLE research we propose the problem of multi-task VL-NLE and show that jointly training on multiple tasks can increase the explanation quality. We discuss the ethical implications of high-quality NLE generation and other issues in recent VL-NLE research.
