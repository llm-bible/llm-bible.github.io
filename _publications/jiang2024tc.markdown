---
layout: publication
title: 'Tc-rag:turing-complete Rag''s Case Study On Medical LLM Systems'
authors: Xinke Jiang, Yue Fang, Rihong Qiu, Haoyu Zhang, Yongxin Xu, Hao Chen, Wentao Zhang, Ruizhe Zhang, Yuchen Fang, Xu Chu, Junfeng Zhao, Yasha Wang
conference: "Arxiv"
year: 2024
bibkey: jiang2024tc
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.09199'}
  - {name: "Code", url: 'https://https://github.com/Artessay/SAMA.git'}
tags: ['Reinforcement Learning', 'RAG', 'Has Code', 'Tools']
---
In the pursuit of enhancing domain-specific Large Language Models (LLMs),
Retrieval-Augmented Generation (RAG) emerges as a promising solution to
mitigate issues such as hallucinations, outdated knowledge, and limited
expertise in highly specialized queries. However, existing approaches to RAG
fall short by neglecting system state variables, which are crucial for ensuring
adaptive control, retrieval halting, and system convergence. In this paper, we
introduce the TC-RAG through rigorous proof, a novel framework that addresses
these challenges by incorporating a Turing Complete System to manage state
variables, thereby enabling more efficient and accurate knowledge retrieval. By
leveraging a memory stack system with adaptive retrieval, reasoning, and
planning capabilities, TC-RAG not only ensures the controlled halting of
retrieval processes but also mitigates the accumulation of erroneous knowledge
via Push and Pop actions. In the case study of the medical domain, our
extensive experiments on real-world healthcare datasets demonstrate the
superiority of TC-RAG over existing methods in accuracy by over 7.20%. Our
dataset and code have been available at
https://https://github.com/Artessay/SAMA.git.
