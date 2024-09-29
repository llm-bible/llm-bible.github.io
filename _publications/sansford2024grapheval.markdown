---
layout: publication
title: Grapheval A Knowledge-graph Based LLM Hallucination Evaluation Framework
authors: Sansford Hannah, Richardson Nicholas, Maretic Hermina Petric, Saada Juba Nait
conference: "Arxiv"
year: 2024
bibkey: sansford2024grapheval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10793"}
tags: ['Applications', 'RAG', 'Tools']
---
Methods to evaluate Large Language Model (LLM) responses and detect inconsistencies also known as hallucinations with respect to the provided knowledge are becoming increasingly important for LLM applications. Current metrics fall short in their ability to provide explainable decisions systematically check all pieces of information in the response and are often too computationally expensive to be used in practice. We present GraphEval a hallucination evaluation framework based on representing information in Knowledge Graph (KG) structures. Our method identifies the specific triples in the KG that are prone to hallucinations and hence provides more insight into where in the response a hallucination has occurred if at all than previous methods. Furthermore using our approach in conjunction with state-of-the-art natural language inference (NLI) models leads to an improvement in balanced accuracy on various hallucination benchmarks compared to using the raw NLI models. Lastly we explore the use of GraphEval for hallucination correction by leveraging the structure of the KG a method we name GraphCorrect and demonstrate that the majority of hallucinations can indeed be rectified.
