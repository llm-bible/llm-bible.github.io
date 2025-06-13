---
layout: publication
title: 'The Power Of Adaptation: Boosting In-context Learning Through Adaptive Prompting'
authors: Shuzhang Cai, Twumasi Mensah-boateng, Xander Kuksov, Jing Yuan, Shaojie Tang
conference: "Arxiv"
year: 2024
bibkey: cai2024power
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.17891"}
tags: ['RAG', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) have demonstrated exceptional abilities across a
broad range of language-related tasks, including generating solutions to
complex reasoning problems. An effective technique to enhance LLM performance
is in-context learning, which encourages a step-by-step reasoning process by
including explanatory examples to guide the model's responses. However,
selecting appropriate exemplars for the model poses a challenge, as each
dataset demands a distinct set of exemplars to enable the LLM to learn
effectively and perform well on the test set. Current studies often rely on
uncertainty- or diversity-based selection strategies to select exemplars for
annotation and to improve model learning. However, these studies typically
employ a non-adaptive approach, selecting a set of exemplars all at once. We
argue that this non-adaptive strategy may result in a set of exemplars with
high redundancy in terms of the knowledge covered, ultimately reducing their
overall informativeness. To address this limitation, we propose
\textsc\{Adaptive-Prompt\}, a novel method that adaptively selects exemplars by
leveraging model feedback from previously chosen exemplars. Experimental
results show that \textsc\{Adaptive-Prompt\} significantly enhances LLM
performance across a variety of reasoning tasks.
