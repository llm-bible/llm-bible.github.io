---
layout: publication
title: 'Breaking Focus: Contextual Distraction Curse In Large Language Models'
authors: Yue Huang, Yanbo Wang, Zixiang Xu, Chujie Gao, Siyuan Wu, Jiayi Ye, Xiuying Chen, Pin-yu Chen, Xiangliang Zhang
conference: "Arxiv"
year: 2025
bibkey: huang2025breaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01609"}
  - {name: "Code", url: "https://github.com/wyf23187/LLM_CDV"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Has Code', 'Applications', 'Attention Mechanism']
---
Recent advances in Large Language Models (LLMs) have revolutionized
generative systems, achieving excellent performance across diverse domains.
Although these models perform well in controlled environments, their real-world
applications frequently encounter inputs containing both essential and
irrelevant details. Our investigation has revealed a critical vulnerability in
LLMs, which we term Contextual Distraction Vulnerability (CDV). This phenomenon
arises when models fail to maintain consistent performance on questions
modified with semantically coherent but irrelevant context. To systematically
investigate this vulnerability, we propose an efficient tree-based search
methodology to automatically generate CDV examples. Our approach successfully
generates CDV examples across four datasets, causing an average performance
degradation of approximately 45% in state-of-the-art LLMs. To address this
critical issue, we explore various mitigation strategies and find that
post-targeted training approaches can effectively enhance model robustness
against contextual distractions. Our findings highlight the fundamental nature
of CDV as an ability-level challenge rather than a knowledge-level issue since
models demonstrate the necessary knowledge by answering correctly in the
absence of distractions. This calls the community's attention to address CDV
during model development to ensure reliability. The code is available at
https://github.com/wyf23187/LLM_CDV.
