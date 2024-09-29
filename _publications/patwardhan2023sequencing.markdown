---
layout: publication
title: Sequencing Matters A Generate-retrieve-generate Model For Building Conversational Agents
authors: Patwardhan Quinn, Yang Grace Hui
conference: "Arxiv"
year: 2023
bibkey: patwardhan2023sequencing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09513"}
tags: ['Agentic', 'Applications', 'BERT', 'Model Architecture', 'RAG']
---
This paper contains what the Georgetown InfoSense group has done in regard to solving the challenges presented by TREC iKAT 2023. Our submitted runs outperform the median runs by a significant margin exhibiting superior performance in nDCG across various cut numbers and in overall success rate. Our approach uses a Generate-Retrieve-Generate method which weve found to greatly outpace Retrieve-Then-Generate approaches for the purposes of iKAT. Our solution involves the use of Large Language Models (LLMs) for initial answers answer grounding by BM25 passage quality filtering by logistic regression and answer generation by LLMs again. We leverage several purpose-built Language Models including BERT Chat-based and text-to-transfer-based models for text understanding classification generation and summarization. The official results of the TREC evaluation contradict our initial self-evaluation which may suggest that a decrease in the reliance on our retrieval and classification methods is better. Nonetheless our findings suggest that the sequence of involving these different components matters where we see an essentiality of using LLMs before using search engines.
