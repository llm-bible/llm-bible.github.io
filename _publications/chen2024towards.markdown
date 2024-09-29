---
layout: publication
title: "Towards Boosting Llms-driven Relevance Modeling With Progressive Retrieved Behavior-augmented Prompting"
authors: Chen Zeyuan, Wu Haiyan, Wu Kaixin, Chen Wei, Zhong Mingjie, Xu Jia, Liu Zhongyi, Zhang Wei
conference: "Arxiv"
year: 2024
bibkey: chen2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09439"}
tags: ['Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'TACL', 'Tools']
---
Relevance modeling is a critical component for enhancing user experience in search engines with the primary objective of identifying items that align with users queries. Traditional models only rely on the semantic congruence between queries and items to ascertain relevance. However this approach represents merely one aspect of the relevance judgement and is insufficient in isolation. Even powerful Large Language Models (LLMs) still cannot accurately judge the relevance of a query and an item from a semantic perspective. To augment LLMs-driven relevance modeling this study proposes leveraging user interactions recorded in search logs to yield insights into users implicit search intentions. The challenge lies in the effective prompting of LLMs to capture dynamic search intentions which poses several obstacles in real-world relevance scenarios i.e. the absence of domain-specific knowledge the inadequacy of an isolated prompt and the prohibitive costs associated with deploying LLMs. In response we propose ProRBP a novel Progressive Retrieved Behavior-augmented Prompting framework for integrating search scenario-oriented knowledge with LLMs effectively. Specifically we perform the user-driven behavior neighbors retrieval from the daily search logs to obtain domain-specific knowledge in time retrieving candidates that users consider to meet their expectations. Then we guide LLMs for relevance modeling by employing advanced prompting techniques that progressively improve the outputs of the LLMs followed by a progressive aggregation with comprehensive consideration of diverse aspects. For online serving we have developed an industrial application framework tailored for the deployment of LLMs in relevance modeling. Experiments on real-world industry data and online A/B testing demonstrate our proposal achieves promising performance.
