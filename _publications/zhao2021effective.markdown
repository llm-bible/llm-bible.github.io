---
layout: publication
title: 'Effective Sequence-to-sequence Dialogue State Tracking'
authors: Jeffrey Zhao, Mahdis Mahdieh, Ye Zhang, Yuan Cao, Yonghui Wu
conference: "Arxiv"
year: 2021
bibkey: zhao2021effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.13990"}
tags: ['Training Techniques', 'Pre-Training', 'Applications', 'Reinforcement Learning']
---
Sequence-to-sequence models have been applied to a wide variety of NLP tasks,
but how to properly use them for dialogue state tracking has not been
systematically investigated. In this paper, we study this problem from the
perspectives of pre-training objectives as well as the formats of context
representations. We demonstrate that the choice of pre-training objective makes
a significant difference to the state tracking quality. In particular, we find
that masked span prediction is more effective than auto-regressive language
modeling. We also explore using Pegasus, a span prediction-based pre-training
objective for text summarization, for the state tracking model. We found that
pre-training for the seemingly distant summarization task works surprisingly
well for dialogue state tracking. In addition, we found that while recurrent
state context representation works also reasonably well, the model may have a
hard time recovering from earlier mistakes. We conducted experiments on the
MultiWOZ 2.1-2.4, WOZ 2.0, and DSTC2 datasets with consistent observations.
