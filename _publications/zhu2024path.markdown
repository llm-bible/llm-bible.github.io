---
layout: publication
title: 'Path-consistency: Prefix Enhancement For Efficient Inference In LLM'
authors: Jiace Zhu, Yingtao Shen, Jie Zhao, An Zou
conference: "Arxiv"
year: 2024
bibkey: zhu2024path
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01281"}
tags: ['RAG', 'Applications', 'Efficiency and Optimization', 'Reinforcement Learning']
---
To enhance the reasoning capabilities of large language models (LLMs),
self-consistency has gained significant popularity by combining multiple
sampling with majority voting. However, the state-of-the-art self-consistency
approaches consume substantial computational resources and lead to significant
additional time costs due to the multiple sampling. This prevents its full
potential from being realized in scenarios where computational resources are
critical. To improve the inference efficiency, this paper introduces
\textit\{path-consistency\}, a method that leverages the confidence of answers
generated in earlier branches to identify the prefix of the most promising
path. By dynamically guiding the generation of subsequent branches based on
this prefix, the \textit\{path-consistency\} mitigates both the errors and
redundancies from random or less useful sampling in self-consistency. As a
result, it can significantly accelerate the inference process by reducing the
number of tokens generated. Our extensive empirical evaluation shows that the
\textit\{path-consistency\} achieves significant acceleration in inference
latency ranging from \\(7.8%\\) to \\(40.5%\\), while maintaining or even improving
task accuracy across different datasets, including mathematical reasoning,
common sense reasoning, symbolic reasoning, and code generation.
