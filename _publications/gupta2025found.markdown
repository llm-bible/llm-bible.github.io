---
layout: publication
title: 'Found In Translation: Measuring Multilingual LLM Consistency As Simple As Translate Then Evaluate'
authors: Ashim Gupta, Maitrey Mehta, Zhichao Xu, Vivek Srikumar
conference: "Arxiv"
year: 2025
bibkey: gupta2025found
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21999"}
tags: ['Tools']
---
Large language models (LLMs) provide detailed and impressive responses to queries in English. However, are they really consistent at responding to the same query in other languages? The popular way of evaluating for multilingual performance of LLMs requires expensive-to-collect annotated datasets. Further, evaluating for tasks like open-ended generation, where multiple correct answers may exist, is nontrivial. Instead, we propose to evaluate the predictability of model response across different languages. In this work, we propose a framework to evaluate LLM's cross-lingual consistency based on a simple Translate then Evaluate strategy. We instantiate this evaluation framework along two dimensions of consistency: information and empathy. Our results reveal pronounced inconsistencies in popular LLM responses across thirty languages, with severe performance deficits in certain language families and scripts, underscoring critical weaknesses in their multilingual capabilities. These findings necessitate cross-lingual evaluations that are consistent along multiple dimensions. We invite practitioners to use our framework for future multilingual LLM benchmarking.
