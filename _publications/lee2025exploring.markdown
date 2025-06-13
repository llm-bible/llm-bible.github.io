---
layout: publication
title: 'Exploring In-context Example Generation For Machine Translation'
authors: Dohyun Lee, Seungil Chad Lee, Chanwoo Yang, Yujin Baek, Jaegul Choo
conference: "Arxiv"
year: 2025
bibkey: lee2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00507"}
  - {name: "Code", url: "https://github.com/aiclaudev/DAT"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Has Code', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) have demonstrated strong performance across various tasks, leveraging their exceptional in-context learning ability with only a few examples. Accordingly, the selection of optimal in-context examples has been actively studied in the field of machine translation. However, these studies presuppose the presence of a demonstration pool with human-annotated pairs, making them less applicable to low-resource languages where such an assumption is challenging to meet. To overcome this limitation, this paper explores the research direction of in-context example generation for machine translation. Specifically, we propose Demonstration Augmentation for Translation (DAT), a simple yet effective approach that generates example pairs without relying on any external resources. This method builds upon two prior criteria, relevance and diversity, which have been highlighted in previous work as key factors for in-context example selection. Through experiments and analysis on low-resource languages where human-annotated pairs are scarce, we show that DAT achieves superior translation quality compared to the baselines. Furthermore, we investigate the potential of progressively accumulating generated pairs during test time to build and reuse a demonstration pool. Our implementation is publicly available at https://github.com/aiclaudev/DAT.
