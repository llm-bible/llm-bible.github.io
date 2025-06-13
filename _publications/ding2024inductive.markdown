---
layout: publication
title: 'Inductive Generative Recommendation Via Retrieval-based Speculation'
authors: Yijie Ding, Yupeng Hou, Jiacheng Li, Julian Mcauley
conference: "Arxiv"
year: 2024
bibkey: ding2024inductive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02939"}
  - {name: "Code", url: "https://github.com/Jamesding000/SpecGR"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Generative recommendation (GR) is an emerging paradigm that tokenizes items
into discrete tokens and learns to autoregressively generate the next tokens as
predictions. Although effective, GR models operate in a transductive setting,
meaning they can only generate items seen during training without applying
heuristic re-ranking strategies. In this paper, we propose SpecGR, a
plug-and-play framework that enables GR models to recommend new items in an
inductive setting. SpecGR uses a drafter model with inductive capability to
propose candidate items, which may include both existing items and new items.
The GR model then acts as a verifier, accepting or rejecting candidates while
retaining its strong ranking capabilities. We further introduce the guided
re-drafting technique to make the proposed candidates more aligned with the
outputs of generative recommendation models, improving the verification
efficiency. We consider two variants for drafting: (1) using an auxiliary
drafter model for better flexibility, or (2) leveraging the GR model's own
encoder for parameter-efficient self-drafting. Extensive experiments on three
real-world datasets demonstrate that SpecGR exhibits both strong inductive
recommendation ability and the best overall performance among the compared
methods. Our code is available at: https://github.com/Jamesding000/SpecGR.
