---
layout: publication
title: 'A + B: A General Generator-reader Framework For Optimizing Llms To Unleash Synergy Potential'
authors: Tang Wei, Cao Yixin, Ying Jiahao, Wang Bo, Zhao Yuyue, Liao Yong, Zhou Pengyuan
conference: "Arxiv"
year: 2024
bibkey: tang2024general
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03963"}
tags: ['RAG', 'Responsible AI', 'Tools']
---
Retrieval-Augmented Generation (RAG) is an effective solution to supplement necessary knowledge to large language models (LLMs). Targeting its bottleneck of retriever performance generate-then-read pipeline is proposed to replace the retrieval stage with generation from the LLM itself. Although promising this research direction is underexplored and still cannot work in the scenario when source knowledge is given. In this paper we formalize a general A + B framework with varying combinations of foundation models and types for systematic investigation. We explore the efficacy of the base and chat versions of LLMs and found their different functionalities suitable for generator A and reader B respectively. Their combinations consistently outperform single models especially in complex scenarios. Furthermore we extend the application of the A + B framework to scenarios involving source documents through continuous learning enabling the direct integration of external knowledge into LLMs. This approach not only facilitates effective acquisition of new knowledge but also addresses the challenges of safety and helpfulness post-adaptation. The paper underscores the versatility of the A + B framework demonstrating its potential to enhance the practical application of LLMs across various domains.
