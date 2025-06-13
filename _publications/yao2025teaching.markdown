---
layout: publication
title: 'Expandr: Teaching Dense Retrievers Beyond Queries With LLM Guidance'
authors: Sijia Yao, Pengcheng Huang, Zhenghao Liu, Yu Gu, Yukun Yan, Shi Yu, Ge Yu
conference: "Arxiv"
year: 2025
bibkey: yao2025teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17057"}
  - {name: "Code", url: "https://github.com/NEUIR/ExpandR"}
tags: ['Tools', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Large language models (LLMs) have demonstrated significant potential in enhancing dense retrieval through query augmentation. However, most existing methods treat the LLM and the retriever as separate modules, overlooking the alignment between generation and ranking objectives. In this work, we propose ExpandR, a unified LLM-augmented dense retrieval framework that jointly optimizes both the LLM and the retriever. ExpandR employs the LLM to generate semantically rich query expansions, which are leveraged to enhance the retriever's training. Simultaneously, the LLM is trained using Direct Preference Optimization (DPO), guided by a carefully designed reward function that balances retrieval effectiveness and generation consistency. This joint optimization paradigm enables mutual adaptation between the LLM and the retriever, resulting in query expansions that are both informative and well-suited for retrieval. Experimental results on multiple benchmarks show that ExpandR consistently outperforms strong baselines, achieving more than a 5% improvement in retrieval performance. All codes are available at https://github.com/NEUIR/ExpandR.
