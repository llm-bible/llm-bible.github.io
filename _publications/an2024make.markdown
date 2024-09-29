---
layout: publication
title: Make Your LLM Fully Utilize The Context
authors: An Shengnan, Ma Zexiong, Lin Zeqi, Zheng Nanning, Lou Jian-guang
conference: "Arxiv"
year: 2024
bibkey: an2024make
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16811"}
  - {name: "Code", url: "https://github.com/microsoft/FILM"}
tags: ['Applications', 'Has Code', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
While many contemporary large language models (LLMs) can process lengthy input they still struggle to fully utilize information within the long context known as the lost45;in45;the45;middle challenge. We hypothesize that it stems from insufficient explicit supervision during the long45;context training which fails to emphasize that any position in a long context can hold crucial information. Based on this intuition our study presents information45;intensive (IN2) training a purely data45;driven solution to overcome lost45;in45;the45;middle. Specifically IN2 training leverages a synthesized long45;context question45;answer dataset where the answer requires (1) fine45;grained information awareness on a short segment (~128 tokens) within a synthesized long context (4K45;32K tokens) and (2) the integration and reasoning of information from two or more short segments. Through applying this information45;intensive training on Mistral45;7B we present FILM45;7B (FILl45;in45;the45;Middle). To thoroughly assess the ability of FILM45;7B for utilizing long contexts we design three probing tasks that encompass various context styles (document code and structured45;data context) and information retrieval patterns (forward backward and bi45;directional retrieval). The probing results demonstrate that FILM45;7B can robustly retrieve information from different positions in its 32K context window. Beyond these probing tasks FILM45;7B significantly improves the performance on real45;world long45;context tasks (e.g. 23.545;26.9 F1 score on NarrativeQA) while maintaining a comparable performance on short45;context tasks (e.g. 59.345;59.2 accuracy on MMLU). Github Link https://github.com/microsoft/FILM.
