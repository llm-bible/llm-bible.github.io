---
layout: publication
title: 'CRAG -- Comprehensive RAG Benchmark'
authors: Xiao Yang, Kai Sun, Hao Xin, Yushi Sun, Nikita Bhalla, Xiangsen Chen, Sajal Choudhary, Rongze Daniel Gui, Ziran Will Jiang, Ziyu Jiang, Lingkun Kong, Brian Moran, Jiaqi Wang, Yifan Ethan Xu, An Yan, Chenyu Yang, Eting Yuan, Hanwen Zha, Nan Tang, Lei Chen, Nicolas Scheffer, Yue Liu, Nirav Shah, Rakesh Wanga, Anuj Kumar, Wen-tau Yih, Xin Luna Dong
conference: "Arxiv"
year: 2024
bibkey: yang2024crag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04744"}
  - {name: "Code", url: "https://github.com/facebookresearch/CRAG/"}
tags: ['Tools', 'Reinforcement Learning', 'RAG', 'KDD', 'Has Code', 'Applications']
---
Retrieval-Augmented Generation (RAG) has recently emerged as a promising
solution to alleviate Large Language Model (LLM)'s deficiency in lack of
knowledge. Existing RAG datasets, however, do not adequately represent the
diverse and dynamic nature of real-world Question Answering (QA) tasks. To
bridge this gap, we introduce the Comprehensive RAG Benchmark (CRAG), a factual
question answering benchmark of 4,409 question-answer pairs and mock APIs to
simulate web and Knowledge Graph (KG) search. CRAG is designed to encapsulate a
diverse array of questions across five domains and eight question categories,
reflecting varied entity popularity from popular to long-tail, and temporal
dynamisms ranging from years to seconds. Our evaluation of this benchmark
highlights the gap to fully trustworthy QA. Whereas most advanced LLMs achieve
<=34% accuracy on CRAG, adding RAG in a straightforward manner improves the
accuracy only to 44%. State-of-the-art industry RAG solutions only answer 63%
of questions without any hallucination. CRAG also reveals much lower accuracy
in answering questions regarding facts with higher dynamism, lower popularity,
or higher complexity, suggesting future research directions. The CRAG benchmark
laid the groundwork for a KDD Cup 2024 challenge and attracted thousands of
participants and submissions. We commit to maintaining CRAG to serve research
communities in advancing RAG solutions and general QA solutions. CRAG is
available at https://github.com/facebookresearch/CRAG/.
