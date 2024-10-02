---
layout: publication
title: 'Plasma: Making Small Language Models Better Procedural Knowledge Models For (counterfactual) Planning'
authors: Brahman Faeze, Bhagavatula Chandra, Pyatkin Valentina, Hwang Jena D., Li Xiang Lorraine, Arai Hirona J., Sanyal Soumya, Sakaguchi Keisuke, Ren Xiang, Choi Yejin
conference: "Arxiv"
year: 2023
bibkey: brahman2023making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.19472"}
tags: ['Distillation', 'Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Tools']
---
Procedural planning, which entails decomposing a high-level goal into a sequence of temporally ordered steps, is an important yet intricate task for machines. It involves integrating common-sense knowledge to reason about complex contextualized situations that are often counterfactual, e.g. scheduling a doctor's appointment without a phone. While current approaches show encouraging results using large language models (LLMs), they are hindered by drawbacks such as costly API calls and reproducibility issues. In this paper, we advocate planning using smaller language models. We present PlaSma, a novel two-pronged approach to endow small language models with procedural knowledge and (counterfactual) planning capabilities. More concretely, we develop symbolic procedural knowledge distillation to enhance the implicit knowledge in small language models and an inference-time algorithm to facilitate more structured and accurate reasoning. In addition, we introduce a novel task, Counterfactual Planning, that requires a revision of a plan to cope with a counterfactual situation. In both the original and counterfactual setting, we show that orders-of-magnitude smaller models (770M-11B parameters) can compete and often surpass their larger teacher models' capabilities.
