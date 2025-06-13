---
layout: publication
title: 'Is Llms Hallucination Usable? Llm-based Negative Reasoning For Fake News Detection'
authors: Chaowei Zhang, Zongling Feng, Zewei Zhang, Jipeng Qiang, Guandong Xu, Yun Li
conference: "Arxiv"
year: 2025
bibkey: zhang2025is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.09153"}
tags: ['Fine-Tuning', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
The questionable responses caused by knowledge hallucination may lead to
LLMs' unstable ability in decision-making. However, it has never been
investigated whether the LLMs' hallucination is possibly usable to generate
negative reasoning for facilitating the detection of fake news. This study
proposes a novel supervised self-reinforced reasoning rectification approach -
SR\\(^3\\) that yields both common reasonable reasoning and wrong understandings
(negative reasoning) for news via LLMs reflection for semantic consistency
learning. Upon that, we construct a negative reasoning-based news learning
model called - *NRFE*, which leverages positive or negative news-reasoning
pairs for learning the semantic consistency between them. To avoid the impact
of label-implicated reasoning, we deploy a student model - *NRFE-D* that
only takes news content as input to inspect the performance of our method by
distilling the knowledge from *NRFE*. The experimental results verified on
three popular fake news datasets demonstrate the superiority of our method
compared with three kinds of baselines including prompting on LLMs, fine-tuning
on pre-trained SLMs, and other representative fake news detection methods.
