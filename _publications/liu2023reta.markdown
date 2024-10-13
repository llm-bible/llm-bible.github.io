---
layout: publication
title: 'RETA-LLM: A Retrieval-augmented Large Language Model Toolkit'
authors: Liu Jiongnan, Jin Jiajie, Wang Zihan, Cheng Jiehan, Dou Zhicheng, Wen Ji-rong
conference: "Arxiv"
year: 2023
bibkey: liu2023reta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.05212"}
  - {name: "Code", url: "https://github.com/RUC-GSAI/YuLan-IR/tree/main/RETA-LLM"}
tags: ['Applications', 'Has Code', 'RAG', 'Reinforcement Learning']
---
Although Large Language Models (LLMs) have demonstrated extraordinary
capabilities in many domains, they still have a tendency to hallucinate and
generate fictitious responses to user requests. This problem can be alleviated
by augmenting LLMs with information retrieval (IR) systems (also known as
retrieval-augmented LLMs). Applying this strategy, LLMs can generate more
factual texts in response to user input according to the relevant content
retrieved by IR systems from external corpora as references. In addition, by
incorporating external knowledge, retrieval-augmented LLMs can answer in-domain
questions that cannot be answered by solely relying on the world knowledge
stored in parameters. To support research in this area and facilitate the
development of retrieval-augmented LLM systems, we develop RETA-LLM, a
\{RET\}reival-\{A\}ugmented LLM toolkit. In RETA-LLM, we create a complete pipeline
to help researchers and users build their customized in-domain LLM-based
systems. Compared with previous retrieval-augmented LLM systems, RETA-LLM
provides more plug-and-play modules to support better interaction between IR
systems and LLMs, including \{request rewriting, document retrieval, passage
extraction, answer generation, and fact checking\} modules. Our toolkit is
publicly available at https://github.com/RUC-GSAI/YuLan-IR/tree/main/RETA-LLM.
