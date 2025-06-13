---
layout: publication
title: 'Investigating The Role Of Prompting And External Tools In Hallucination Rates Of Large Language Models'
authors: Liam Barkley, Brink Van Der Merwe
conference: "Arxiv"
year: 2024
bibkey: barkley2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19385"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Prompting', 'Attention Mechanism']
---
Large Language Models (LLMs) are powerful computational models trained on
extensive corpora of human-readable text, enabling them to perform
general-purpose language understanding and generation. LLMs have garnered
significant attention in both industry and academia due to their exceptional
performance across various natural language processing (NLP) tasks. Despite
these successes, LLMs often produce inaccuracies, commonly referred to as
hallucinations. Prompt engineering, the process of designing and formulating
instructions for LLMs to perform specific tasks, has emerged as a key approach
to mitigating hallucinations. This paper provides a comprehensive empirical
evaluation of different prompting strategies and frameworks aimed at reducing
hallucinations in LLMs. Various prompting techniques are applied to a broad set
of benchmark datasets to assess the accuracy and hallucination rate of each
method. Additionally, the paper investigates the influence of tool-calling
agents (LLMs augmented with external tools to enhance their capabilities beyond
language generation) on hallucination rates in the same benchmarks. The
findings demonstrate that the optimal prompting technique depends on the type
of problem, and that simpler techniques often outperform more complex methods
in reducing hallucinations. Furthermore, it is shown that LLM agents can
exhibit significantly higher hallucination rates due to the added complexity of
external tool usage.
