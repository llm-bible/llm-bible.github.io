---
layout: publication
title: 'Predicting Text Preference Via Structured Comparative Reasoning'
authors: Jing Nathan Yan, Tianqi Liu, Justin T Chiu, Jiaming Shen, Zhen Qin, Yue Yu, Yao Zhao, Charu Lakshmanan, Yair Kurzion, Alexander M. Rush, Jialu Liu, Michael Bendersky
conference: "Arxiv"
year: 2023
bibkey: yan2023predicting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.08390'}
tags: ['Reinforcement Learning', 'Prompting', 'Applications']
---
Comparative reasoning plays a crucial role in text preference prediction;
however, large language models (LLMs) often demonstrate inconsistencies in
their reasoning. While approaches like Chain-of-Thought improve accuracy in
many other settings, they struggle to consistently distinguish the similarities
and differences of complex texts. We introduce SC, a prompting approach that
predicts text preferences by generating structured intermediate comparisons. SC
begins by proposing aspects of comparison, followed by generating textual
comparisons under each aspect. We select consistent comparisons with a pairwise
consistency comparator that ensures each aspect's comparisons clearly
distinguish differences between texts, significantly reducing hallucination and
improving consistency. Our comprehensive evaluations across various NLP tasks,
including summarization, retrieval, and automatic rating, demonstrate that SC
equips LLMs to achieve state-of-the-art performance in text preference
prediction.
