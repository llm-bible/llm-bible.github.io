---
layout: publication
title: 'Hybrid Retrieval-augmented Generation For Real-time Composition Assistance'
authors: Xia Menglin, Zhang Xuchao, Couturier Camille, Zheng Guoqing, Rajmohan Saravan, Ruhle Victor
conference: "Arxiv"
year: 2023
bibkey: xia2023hybrid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.04215"}
tags: ['RAG', 'Tools']
---
Retrieval augmentation enhances performance of traditional language models by incorporating additional context. However, the computational demands for retrieval augmented large language models (LLMs) pose a challenge when applying them to real-time tasks, such as composition assistance. To address this limitation, we propose the Hybrid Retrieval-Augmented Generation (HybridRAG) framework, a novel approach that efficiently combines a cloud-based LLM with a smaller, client-side, language model through retrieval augmented memory. This integration enables the client model to generate effective responses, benefiting from the LLM's capabilities and contextual information. Additionally, through an asynchronous memory update mechanism, the client model can deliver real-time completions swiftly to user inputs without the need to wait for responses from the cloud. Our experiments on five benchmark datasets demonstrate that HybridRAG significantly improves utility over client-only models while maintaining low latency.
