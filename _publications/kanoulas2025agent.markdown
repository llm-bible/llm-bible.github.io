---
layout: publication
title: 'Agent-centric Information Access'
authors: Evangelos Kanoulas, Panagiotis Eustratiadis, Yongkang Li, Yougang Lyu, Vaishali Pal, Gabrielle Poerwawinata, Jingfen Qiao, Zihan Wang
conference: "Arxiv"
year: 2025
bibkey: kanoulas2025agent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19298"}
tags: ['RAG', 'Agentic', 'Security', 'Tools']
---
As large language models (LLMs) become more specialized, we envision a future
where millions of expert LLMs exist, each trained on proprietary data and
excelling in specific domains. In such a system, answering a query requires
selecting a small subset of relevant models, querying them efficiently, and
synthesizing their responses. This paper introduces a framework for
agent-centric information access, where LLMs function as knowledge agents that
are dynamically ranked and queried based on their demonstrated expertise.
Unlike traditional document retrieval, this approach requires inferring
expertise on the fly, rather than relying on static metadata or predefined
model descriptions. This shift introduces several challenges, including
efficient expert selection, cost-effective querying, response aggregation
across multiple models, and robustness against adversarial manipulation. To
address these issues, we propose a scalable evaluation framework that leverages
retrieval-augmented generation and clustering techniques to construct and
assess thousands of specialized models, with the potential to scale toward
millions.
