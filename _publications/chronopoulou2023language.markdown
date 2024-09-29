---
layout: publication
title: Language And Task Arithmetic With Parameter45;efficient Layers For Zero45;shot Summarization
authors: Chronopoulou Alexandra, Pfeiffer Jonas, Maynez Joshua, Wang Xinyi, Ruder Sebastian, Agrawal Priyanka
conference: "Arxiv"
year: 2023
bibkey: chronopoulou2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09344"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Parameter45;efficient fine45;tuning (PEFT) using labeled task data can significantly improve the performance of large language models (LLMs) on the downstream task. However there are 7000 languages in the world and many of these languages lack labeled data for real45;world language generation tasks. In this paper we propose to improve zero45;shot cross45;lingual transfer by composing language or task specialized parameters. Our method composes language and task PEFT modules via element45;wise arithmetic operations to leverage unlabeled data and English labeled data. We extend our approach to cases where labeled data from more languages is available and propose to arithmetically compose PEFT modules trained on languages related to the target. Empirical results on summarization demonstrate that our method is an effective strategy that obtains consistent gains using minimal training of PEFT modules.
