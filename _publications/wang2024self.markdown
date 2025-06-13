---
layout: publication
title: 'Self-updatable Large Language Models By Integrating Context Into Model Parameters'
authors: Yu Wang, Xinshuang Liu, Xiusi Chen, Sean O'brien, Junda Wu, Julian Mcauley
conference: "Arxiv"
year: 2024
bibkey: wang2024self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.00487'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Tools']
---
Despite significant advancements in large language models (LLMs), the rapid
and frequent integration of small-scale experiences, such as interactions with
surrounding objects, remains a substantial challenge. Two critical factors in
assimilating these experiences are (1) Efficacy: the ability to accurately
remember recent events; (2) Retention: the capacity to recall long-past
experiences. Current methods either embed experiences within model parameters
using continual learning, model editing, or knowledge distillation techniques,
which often struggle with rapid updates and complex interactions, or rely on
external storage to achieve long-term retention, thereby increasing storage
requirements. In this paper, we propose SELF-PARAM (Self-Updatable Large
Language Models with Parameter Integration). SELF-PARAM requires no extra
parameters while ensuring near-optimal efficacy and long-term retention. Our
method employs a training objective that minimizes the Kullback-Leibler (KL)
divergence between the predictions of an original model (with access to
contextual information) and a target model (without such access). By generating
diverse question-answer pairs related to the knowledge and minimizing the KL
divergence across this dataset, we update the target model to internalize the
knowledge seamlessly within its parameters. Evaluations on question-answering
and conversational recommendation tasks demonstrate that SELF-PARAM
significantly outperforms existing methods, even when accounting for non-zero
storage requirements. This advancement paves the way for more efficient and
scalable integration of experiences in large language models by embedding
knowledge directly into model parameters.
