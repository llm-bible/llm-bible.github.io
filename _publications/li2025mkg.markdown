---
layout: publication
title: 'Mkg-rank: Enhancing Large Language Models With Knowledge Graph For Multilingual Medical Question Answering'
authors: Feiyang Li, Yingjian Chen, Haoran Liu, Rui Yang, Han Yuan, Yuang Jiang, Tianxiao Li, Edison Marrese Taylor, Hossein Rouhizadeh, Yusuke Iwasawa, Douglas Teodoro, Yutaka Matsuo, Irene Li
conference: "Arxiv"
year: 2025
bibkey: li2025mkg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16131"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) have shown remarkable progress in medical
question answering (QA), yet their effectiveness remains predominantly limited
to English due to imbalanced multilingual training data and scarce medical
resources for low-resource languages. To address this critical language gap in
medical QA, we propose Multilingual Knowledge Graph-based Retrieval Ranking
(MKG-Rank), a knowledge graph-enhanced framework that enables English-centric
LLMs to perform multilingual medical QA. Through a word-level translation
mechanism, our framework efficiently integrates comprehensive English-centric
medical knowledge graphs into LLM reasoning at a low cost, mitigating
cross-lingual semantic distortion and achieving precise medical QA across
language barriers. To enhance efficiency, we introduce caching and multi-angle
ranking strategies to optimize the retrieval process, significantly reducing
response times and prioritizing relevant medical knowledge. Extensive
evaluations on multilingual medical QA benchmarks across Chinese, Japanese,
Korean, and Swahili demonstrate that MKG-Rank consistently outperforms
zero-shot LLMs, achieving maximum 35.03% increase in accuracy, while
maintaining an average retrieval time of only 0.0009 seconds.
