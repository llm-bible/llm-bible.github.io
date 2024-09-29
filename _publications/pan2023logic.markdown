---
layout: publication
title: Logic45;lm Empowering Large Language Models With Symbolic Solvers For Faithful Logical Reasoning
authors: Pan Liangming, Albalak Alon, Wang Xinyi, Wang William Yang
conference: "Arxiv"
year: 2023
bibkey: pan2023logic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12295"}
  - {name: "Code", url: "https://github.com/teacherpeterpan/Logic&#45;LLM"}
tags: ['Has Code', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have shown human45;like reasoning abilities but still struggle with complex logical problems. This paper introduces a novel framework Logic45;LM which integrates LLMs with symbolic solvers to improve logical problem45;solving. Our method first utilizes LLMs to translate a natural language problem into a symbolic formulation. Afterward a deterministic symbolic solver performs inference on the formulated problem. We also introduce a self45;refinement module which utilizes the symbolic solvers error messages to revise symbolic formalizations. We demonstrate Logic45;LMs effectiveness on five logical reasoning datasets ProofWriter PrOntoQA FOLIO LogicalDeduction and AR45;LSAT. On average Logic45;LM achieves a significant performance boost of 39.237; over using LLM alone with standard prompting and 18.437; over LLM with chain45;of45;thought prompting. Our findings suggest that Logic45;LM by combining LLMs with symbolic logic offers a promising avenue for faithful logical reasoning. Code and data are publicly available at https://github.com/teacherpeterpan/Logic&#45;LLM.
