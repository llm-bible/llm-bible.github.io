---
layout: publication
title: Halu-J Critique-Based Hallucination Judge
authors: Wang Binjie, Chern Steffi, Chern Ethan, Liu Pengfei
conference: "Arxiv"
year: 2024
bibkey: wang2024halu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12943"}
  - {name: "Code", url: "https://github.com/GAIR-NLP/factool"}
tags: ['GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) frequently generate non-factual content known as hallucinations. Existing retrieval-augmented-based hallucination detection approaches typically address this by framing it as a classification task evaluating hallucinations based on their consistency with retrieved evidence. However this approach usually lacks detailed explanations for these evaluations and does not assess the reliability of these explanations. Furthermore deficiencies in retrieval systems can lead to irrelevant or partially relevant evidence retrieval impairing the detection process. Moreover while real-world hallucination detection requires analyzing multiple pieces of evidence current systems usually treat all evidence uniformly without considering its relevance to the content. To address these challenges we introduce Halu-J a critique-based hallucination judge with 7 billion parameters. Halu-J enhances hallucination detection by selecting pertinent evidence and providing detailed critiques. Our experiments indicate that Halu-J outperforms GPT-4o in multiple-evidence hallucination detection and matches its capability in critique generation and evidence selection. We also introduce ME-FEVER a new dataset designed for multiple-evidence hallucination detection. Our code and dataset can be found in https://github.com/GAIR-NLP/factool .
