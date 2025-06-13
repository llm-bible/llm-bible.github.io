---
layout: publication
title: 'Alleviating Llm-based Generative Retrieval Hallucination In Alipay Search'
authors: Yedan Shen, Kaixin Wu, Yuechen Ding, Jingyuan Wen, Hong Liu, Mingjie Zhong, Zhouhan Lin, Jia Xu, Linjian Mo
conference: "SIGIR 2025"
year: 2025
bibkey: shen2025alleviating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.21098"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Distillation', 'Applications']
---
Generative retrieval (GR) has revolutionized document retrieval with the advent of large language models (LLMs), and LLM-based GR is gradually being adopted by the industry. Despite its remarkable advantages and potential, LLM-based GR suffers from hallucination and generates documents that are irrelevant to the query in some instances, severely challenging its credibility in practical applications. We thereby propose an optimized GR framework designed to alleviate retrieval hallucination, which integrates knowledge distillation reasoning in model training and incorporate decision agent to further improve retrieval precision. Specifically, we employ LLMs to assess and reason GR retrieved query-document (q-d) pairs, and then distill the reasoning data as transferred knowledge to the GR model. Moreover, we utilize a decision agent as post-processing to extend the GR retrieved documents through retrieval model and select the most relevant ones from multi perspectives as the final generative retrieval result. Extensive offline experiments on real-world datasets and online A/B tests on Fund Search and Insurance Search in Alipay demonstrate our framework's superiority and effectiveness in improving search quality and conversion gains.
