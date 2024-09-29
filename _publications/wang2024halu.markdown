---
layout: publication
title: Halu45;j Critique45;based Hallucination Judge
authors: Wang Binjie, Chern Steffi, Chern Ethan, Liu Pengfei
conference: "Arxiv"
year: 2024
bibkey: wang2024halu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12943"}
  - {name: "Code", url: "https://github.com/GAIR&#45;NLP/factool"}
tags: ['GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) frequently generate non45;factual content known as hallucinations. Existing retrieval45;augmented45;based hallucination detection approaches typically address this by framing it as a classification task evaluating hallucinations based on their consistency with retrieved evidence. However this approach usually lacks detailed explanations for these evaluations and does not assess the reliability of these explanations. Furthermore deficiencies in retrieval systems can lead to irrelevant or partially relevant evidence retrieval impairing the detection process. Moreover while real45;world hallucination detection requires analyzing multiple pieces of evidence current systems usually treat all evidence uniformly without considering its relevance to the content. To address these challenges we introduce Halu45;J a critique45;based hallucination judge with 7 billion parameters. Halu45;J enhances hallucination detection by selecting pertinent evidence and providing detailed critiques. Our experiments indicate that Halu45;J outperforms GPT45;4o in multiple45;evidence hallucination detection and matches its capability in critique generation and evidence selection. We also introduce ME45;FEVER a new dataset designed for multiple45;evidence hallucination detection. Our code and dataset can be found in https://github.com/GAIR&#45;NLP/factool .
