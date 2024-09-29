---
layout: publication
title: One Token Can Help! Learning Scalable And Pluggable Virtual Tokens For Retrieval45;augmented Large Language Models
authors: Zhu Yutao, Huang Zhaoheng, Dou Zhicheng, Wen Ji-rong
conference: "Arxiv"
year: 2024
bibkey: zhu2024one
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19670"}
tags: ['Applications', 'Prompting', 'RAG', 'Training Techniques']
---
Retrieval45;augmented generation (RAG) is a promising way to improve large language models (LLMs) for generating more factual accurate and up45;to45;date content. Existing methods either optimize prompts to guide LLMs in leveraging retrieved information or directly fine45;tune LLMs to adapt to RAG scenarios. Although fine45;tuning can yield better performance it often compromises the LLMs general generation capabilities by modifying their parameters. This limitation poses challenges in practical applications especially when LLMs are already deployed as parameter adjustments may affect their original functionality. To address this we propose a novel method that involves learning scalable and pluggable virtual tokens for RAG. By maintaining the LLMs original parameters and fine45;tuning only the embeddings of these pluggable tokens our approach not only enhances LLMs performance but also preserves their general generation capabilities. Furthermore we design several training strategies to improve the scalability flexibility and generalizability of our method. Comprehensive experiments across nine question45;answering tasks demonstrate the superiority of our approach.
