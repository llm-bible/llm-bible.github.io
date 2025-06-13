---
layout: publication
title: 'Towards Typologically Aware Rescoring To Mitigate Unfaithfulness In Lower-resource Languages'
authors: Tsan Tsai Chan, Xin Tong, Thi Thu Uyen Hoang, Barbare Tepnadze, Wojciech Stempniak
conference: "Arxiv"
year: 2025
bibkey: chan2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17664"}
tags: ['Arxiv', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Applications']
---
Multilingual large language models (LLMs) are known to more frequently
generate non-faithful output in resource-constrained languages (Guerreiro et
al., 2023 - arXiv:2303.16104), potentially because these typologically diverse
languages are underrepresented in their training data. To mitigate
unfaithfulness in such settings, we propose using computationally light
auxiliary models to rescore the outputs of larger architectures. As proof of
the feasibility of such an approach, we show that monolingual 4-layer BERT
models pretrained from scratch on less than 700 MB of data without fine-tuning
are able to identify faithful summaries with a mean accuracy of 88.33% in three
genetically unrelated languages that differ in their morphological complexity -
Vietnamese, Polish and Georgian. The same hyperparameter combination moreover
generalises well to three other tasks, suggesting applications for rescoring
beyond improving faithfulness. In order to inform typologically aware model
selection, we also investigate how morphological complexity interacts with
regularisation, model depth and training objectives, ultimately demonstrating
that morphologically complex languages are more likely to benefit from dropout,
while across languages downstream performance is enhanced most by shallow
architectures as well as training using the standard BERT objectives.
