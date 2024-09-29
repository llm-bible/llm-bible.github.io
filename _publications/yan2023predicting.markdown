---
layout: publication
title: 'Predicting Text Preference Via Structured Comparative Reasoning'
authors: Yan Jing Nathan, Liu Tianqi, Chiu Justin T, Shen Jiaming, Qin Zhen, Yu Yue, Zhao Yao, Lakshmanan Charu, Kurzion Yair, Rush Alexander M., Liu Jialu, Bendersky Michael
conference: "Arxiv"
year: 2023
bibkey: yan2023predicting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08390"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning']
---
Comparative reasoning plays a crucial role in text preference prediction; however large language models (LLMs) often demonstrate inconsistencies in their reasoning. While approaches like Chain-of-Thought improve accuracy in many other settings they struggle to consistently distinguish the similarities and differences of complex texts. We introduce SC a prompting approach that predicts text preferences by generating structured intermediate comparisons. SC begins by proposing aspects of comparison followed by generating textual comparisons under each aspect. We select consistent comparisons with a pairwise consistency comparator that ensures each aspects comparisons clearly distinguish differences between texts significantly reducing hallucination and improving consistency. Our comprehensive evaluations across various NLP tasks including summarization retrieval and automatic rating demonstrate that SC equips LLMs to achieve state-of-the-art performance in text preference prediction.
