---
layout: publication
title: 'R1-searcher++: Incentivizing The Dynamic Knowledge Acquisition Of Llms Via Reinforcement Learning'
authors: Huatong Song, Jinhao Jiang, Wenqing Tian, Zhipeng Chen, Yuhuan Wu, Jiahao Zhao, Yingqian Min, Wayne Xin Zhao, Lei Fang, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: song2025incentivizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17005'}
  - {name: "Code", url: 'https://github.com/RUCAIBox/R1-Searcher-plus'}
tags: ['Agentic', 'Has Code', 'RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning']
---
Large Language Models (LLMs) are powerful but prone to hallucinations due to static knowledge. Retrieval-Augmented Generation (RAG) helps by injecting external information, but current methods often are costly, generalize poorly, or ignore the internal knowledge of the model. In this paper, we introduce R1-Searcher++, a novel framework designed to train LLMs to adaptively leverage both internal and external knowledge sources. R1-Searcher++ employs a two-stage training strategy: an initial SFT Cold-start phase for preliminary format learning, followed by RL for Dynamic Knowledge Acquisition. The RL stage uses outcome-supervision to encourage exploration, incorporates a reward mechanism for internal knowledge utilization, and integrates a memorization mechanism to continuously assimilate retrieved information, thereby enriching the model's internal knowledge. By leveraging internal knowledge and external search engine, the model continuously improves its capabilities, enabling efficient retrieval-augmented reasoning. Our experiments demonstrate that R1-Searcher++ outperforms previous RAG and reasoning methods and achieves efficient retrieval. The code is available at https://github.com/RUCAIBox/R1-Searcher-plus.
