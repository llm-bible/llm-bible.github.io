---
layout: publication
title: 'Language And Task Arithmetic With Parameter-efficient Layers For Zero-shot Summarization'
authors: Alexandra Chronopoulou, Jonas Pfeiffer, Joshua Maynez, Xinyi Wang, Sebastian Ruder, Priyanka Agrawal
conference: "Arxiv"
year: 2023
bibkey: chronopoulou2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09344"}
tags: ['Fine-Tuning', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Parameter-efficient fine-tuning (PEFT) using labeled task data can
significantly improve the performance of large language models (LLMs) on the
downstream task. However, there are 7000 languages in the world and many of
these languages lack labeled data for real-world language generation tasks. In
this paper, we propose to improve zero-shot cross-lingual transfer by composing
language or task specialized parameters. Our method composes language and task
PEFT modules via element-wise arithmetic operations to leverage unlabeled data
and English labeled data. We extend our approach to cases where labeled data
from more languages is available and propose to arithmetically compose PEFT
modules trained on languages related to the target. Empirical results on
summarization demonstrate that our method is an effective strategy that obtains
consistent gains using minimal training of PEFT modules.
