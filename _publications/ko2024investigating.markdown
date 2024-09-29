---
layout: publication
title: Investigating How Large Language Models Leverage Internal Knowledge To Perform Complex Reasoning
authors: Ko Miyoung, Park Sue Hyun, Park Joonsuk, Seo Minjoon
conference: "Arxiv"
year: 2024
bibkey: ko2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19502"}
tags: ['RAG', 'Reinforcement Learning']
---
Despite significant advancements there is a limited understanding of how large language models (LLMs) utilize knowledge for reasoning. To address this we propose a method that deconstructs complex real45;world questions into a graph representing each question as a node with parent nodes of background knowledge needed to solve the question. We develop the DepthQA dataset deconstructing questions into three depths (i) recalling conceptual knowledge (ii) applying procedural knowledge and (iii) analyzing strategic knowledge. Based on a hierarchical graph we quantify forward discrepancy discrepancies in LLMs performance on simpler sub45;problems versus complex questions. We also measure backward discrepancy where LLMs answer complex questions but struggle with simpler ones. Our analysis shows that smaller models have more discrepancies than larger models. Additionally guiding models from simpler to complex questions through multi45;turn interactions improves performance across model sizes highlighting the importance of structured intermediate steps in knowledge reasoning. This work enhances our understanding of LLM reasoning and suggests ways to improve their problem45;solving abilities.
