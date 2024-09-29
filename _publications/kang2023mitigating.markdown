---
layout: publication
title: "Ever: Mitigating Hallucination In Large Language Models Through Real-time Verification And Rectification"
authors: Kang Haoqiang, Ni Juntong, Yao Huaxiu
conference: "Arxiv"
year: 2023
bibkey: kang2023mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09114"}
tags: ['Applications', 'Language Modeling', 'RAG']
---
Large Language Models (LLMs) have demonstrated remarkable proficiency in generating fluent text. However they often encounter the challenge of generating inaccurate or hallucinated content. This issue is common in both non-retrieval-based generation and retrieval-augmented generation approaches and existing post-hoc rectification methods may not address the accumulated hallucination errors that may be caused by the snowballing issue especially in reasoning tasks. To tackle these challenges we introduce a novel approach called Real-time Verification and Rectification (Ever). Instead of waiting until the end of the generation process to rectify hallucinations Ever employs a real-time step-wise generation and hallucination rectification strategy. The primary objective is to detect and rectify hallucinations as they occur during the text generation process. When compared to both retrieval-based and non-retrieval-based baselines Ever demonstrates a significant improvement in generating trustworthy and factually accurate text across a diverse range of tasks including short-form QA biography generation and multi-hop reasoning.
