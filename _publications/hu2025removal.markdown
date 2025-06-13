---
layout: publication
title: 'Removal Of Hallucination On Hallucination: Debate-augmented RAG'
authors: Wentao Hu, Wengyu Zhang, Yiyang Jiang, Chen Jason Zhang, Xiaoyong Wei, Qing Li
conference: "Arxiv"
year: 2025
bibkey: hu2025removal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18581"}
  - {name: "Code", url: "https://github.com/Huenao/Debate-Augmented-RAG"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Has Code']
---
Retrieval-Augmented Generation (RAG) enhances factual accuracy by integrating external knowledge, yet it introduces a critical issue: erroneous or biased retrieval can mislead generation, compounding hallucinations, a phenomenon we term Hallucination on Hallucination. To address this, we propose Debate-Augmented RAG (DRAG), a training-free framework that integrates Multi-Agent Debate (MAD) mechanisms into both retrieval and generation stages. In retrieval, DRAG employs structured debates among proponents, opponents, and judges to refine retrieval quality and ensure factual reliability. In generation, DRAG introduces asymmetric information roles and adversarial debates, enhancing reasoning robustness and mitigating factual inconsistencies. Evaluations across multiple tasks demonstrate that DRAG improves retrieval reliability, reduces RAG-induced hallucinations, and significantly enhances overall factual accuracy. Our code is available at https://github.com/Huenao/Debate-Augmented-RAG.
