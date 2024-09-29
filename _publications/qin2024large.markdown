---
layout: publication
title: LAMPO Large Language Models As Preference Machines For Few45;shot Ordinal Classification
authors: Qin Zhen, Wu Junru, Shen Jiaming, Liu Tianqi, Wang Xuanhui
conference: "Arxiv"
year: 2024
bibkey: qin2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03359"}
tags: ['Applications', 'Ethics And Bias', 'Prompting', 'RAG', 'Reinforcement Learning', 'Survey Paper', 'Tools']
---
We introduce LAMPO a novel paradigm that leverages Large Language Models (LLMs) for solving few45;shot multi45;class ordinal classification tasks. Unlike conventional methods which concatenate all demonstration examples with the test instance and prompt LLMs to produce the pointwise prediction our framework uses the LLM as a preference machine that makes a relative comparative decision between the test instance and each demonstration. A self45;supervised method is then introduced to aggregate these binary comparisons into the final ordinal decision. LAMPO addresses several limitations inherent in previous methods including context length constraints ordering biases and challenges associated with absolute point45;wise estimation. Extensive experiments on seven public datasets demonstrate LAMPOs remarkably competitive performance across a diverse spectrum of applications (e.g. movie review analysis and hate speech detection). Notably in certain applications the improvement can be substantial exceeding 2037; in an absolute term. Moreover we believe LAMPO represents an interesting addition to the non45;parametric application layered on top of LLMs as it supports black45;box LLMs without necessitating the outputting of LLMs internal states (e.g. embeddings) as seen in previous approaches.
