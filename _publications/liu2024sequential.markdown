---
layout: publication
title: '\(se^2\): Sequential Example Selection For In-context Learning'
authors: Liu Haoyu, Liu Jianfeng, Huang Shaohan, Zhan Yuefeng, Sun Hao, Deng Weiwei, Wei Furu, Zhang Qi
conference: "Arxiv"
year: 2024
bibkey: liu2024sequential
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13874"}
  - {name: "Code", url: "https://github.com/microsoft/LMOps"}
tags: ['Has Code', 'In Context Learning', 'Prompting', 'RAG', 'Training Techniques']
---
The remarkable capability of large language models (LLMs) for in-context
learning (ICL) needs to be activated by demonstration examples. Prior work has
extensively explored the selection of examples for ICL, predominantly following
the "select then organize" paradigm, such approaches often neglect the internal
relationships between examples and exist an inconsistency between the training
and inference. In this paper, we formulate the problem as a \\(Se\\)quential
\\(Se\\)lection problem and introduce \\(Se^2\\), a sequential-aware method that
leverages the LLM's feedback on varying context, aiding in capturing
inter-relationships and sequential information among examples, significantly
enriching the contextuality and relevance of ICL prompts. Meanwhile, we utilize
beam search to seek and construct example sequences, enhancing both quality and
diversity. Extensive experiments across 23 NLP tasks from 8 distinct categories
illustrate that \\(Se^2\\) markedly surpasses competitive baselines and achieves
42\% relative improvement over random selection. Further in-depth analysis
shows the effectiveness of proposed strategies, highlighting \\(Se^2\\)'s
exceptional stability and adaptability across various scenarios. Code available
at https://github.com/microsoft/LMOps.
