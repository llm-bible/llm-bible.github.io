---
layout: publication
title: 'CRAG -- Comprehensive RAG Benchmark'
authors: Yang Xiao, Sun Kai, Xin Hao, Sun Yushi, Bhalla Nikita, Chen Xiangsen, Choudhary Sajal, Gui Rongze Daniel, Jiang Ziran Will, Jiang Ziyu, Kong Lingkun, Moran Brian, Wang Jiaqi, Xu Yifan Ethan, Yan An, Yang Chenyu, Yuan Eting, Zha Hanwen, Tang Nan, Chen Lei, Scheffer Nicolas, Liu Yue, Shah Nirav, Wanga Rakesh, Kumar Anuj, Yih Wen-tau, Dong Xin Luna
conference: "Arxiv"
year: 2024
bibkey: yang2024crag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04744"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Tools']
---
Retrieval-Augmented Generation (RAG) has recently emerged as a promising solution to alleviate Large Language Model (LLM)'s deficiency in lack of knowledge. Existing RAG datasets, however, do not adequately represent the diverse and dynamic nature of real-world Question Answering (QA) tasks. To bridge this gap, we introduce the Comprehensive RAG Benchmark (CRAG), a factual question answering benchmark of 4,409 question-answer pairs and mock APIs to simulate web and Knowledge Graph (KG) search. CRAG is designed to encapsulate a diverse array of questions across five domains and eight question categories, reflecting varied entity popularity from popular to long-tail, and temporal dynamisms ranging from years to seconds. Our evaluation on this benchmark highlights the gap to fully trustworthy QA. Whereas most advanced LLMs achieve <=34&#37; accuracy on CRAG, adding RAG in a straightforward manner improves the accuracy only to 44&#37;. State-of-the-art industry RAG solutions only answer 63&#37; questions without any hallucination. CRAG also reveals much lower accuracy in answering questions regarding facts with higher dynamism, lower popularity, or higher complexity, suggesting future research directions. The CRAG benchmark laid the groundwork for a KDD Cup 2024 challenge, attracting thousands of participants and submissions within the first 50 days of the competition. We commit to maintaining CRAG to serve research communities in advancing RAG solutions and general QA solutions.
