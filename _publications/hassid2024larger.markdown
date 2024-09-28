---
layout: publication
title: The Larger the Better Improved LLM Code-Generation via Budget Reallocation
authors: Hassid Michael, Remez Tal, Gehring Jonas, Schwartz Roy, Adi Yossi
conference: "Arxiv"
year: 2024
bibkey: hassid2024larger
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00725"}
tags: ['ARXIV', 'Applications', 'LLM']
---
It is a common belief that large language models (LLMs) are better than smaller-sized ones. However larger models also require significantly more time and compute during inference. This begs the question what happens when both models operate under the same budget (e.g. compute run-time). To address this question we analyze code generation LLMs of various sizes and make comparisons such as running a 70B model once vs. generating five outputs from a 13B model. We consider a standard unit-test setup which can be used to select the correct output from the smaller model. Our findings reveal that the repeated use of smaller models can yield consistent improvements with gains of up to 15 across five tasks. On the other hand in scenarios where unit-tests are unavailable a ranking-based selection of candidates from the smaller model falls short of the performance of a single output from larger ones. Our results highlight the potential of using smaller models instead of larger ones and the importance of studying approaches for ranking LLM outputs.
