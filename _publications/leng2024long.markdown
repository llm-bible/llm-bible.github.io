---
layout: publication
title: 'Long Context RAG Performance Of Large Language Models'
authors: Quinn Leng, Jacob Portes, Sam Havens, Matei Zaharia, Michael Carbin
conference: "Arxiv"
year: 2024
bibkey: leng2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.03538"}
tags: ['RAG', 'Survey Paper', 'Applications', 'Reinforcement Learning']
---
Retrieval Augmented Generation (RAG) has emerged as a crucial technique for
enhancing the accuracy of Large Language Models (LLMs) by incorporating
external information. With the advent of LLMs that support increasingly longer
context lengths, there is a growing interest in understanding how these models
perform in RAG scenarios. Can these new long context models improve RAG
performance? This paper presents a comprehensive study of the impact of
increased context length on RAG performance across 20 popular open source and
commercial LLMs. We ran RAG workflows while varying the total context length
from 2,000 to 128,000 tokens (and 2 million tokens when possible) on three
domain-specific datasets, and report key insights on the benefits and
limitations of long context in RAG applications. Our findings reveal that while
retrieving more documents can improve performance, only a handful of the most
recent state of the art LLMs can maintain consistent accuracy at long context
above 64k tokens. We also identify distinct failure modes in long context
scenarios, suggesting areas for future research.
