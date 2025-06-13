---
layout: publication
title: 'Unitcoder: Scalable Iterative Code Synthesis With Unit Test Guidance'
authors: Yichuan Ma, Yunfan Shao, Peiji Li, Demin Song, Qipeng Guo, Linyang Li, Xipeng Qiu, Kai Chen
conference: "Arxiv"
year: 2025
bibkey: ma2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11460"}
  - {name: "Code", url: "https://github.com)"}
tags: ['Pre-Training', 'Tools', 'Ethics and Bias', 'Applications', 'RAG', 'Training Techniques', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
various tasks, yet code generation remains a major challenge. Current
approaches for obtaining high-quality code data primarily focus on (i)
collecting large-scale pre-training data and (ii) synthesizing instruction data
through prompt engineering with powerful models. While pre-training data faces
quality consistency issues, instruction-based synthesis suffers from limited
instruction diversity and inherent biases of LLMs. To address this gap, we
introduce UnitCoder, a systematic pipeline leveraging model-generated unit
tests to both guide and validate the code generation process. Combined with
large-scale package-based retrieval from pre-training corpus, we generate a
dataset of 500K+ verifiable programs containing diverse API calls. Evaluations
on multiple Python benchmarks (BigCodeBench, HumanEval, MBPP) demonstrate that
models fine-tuned on our synthetic data exhibit consistent performance
improvements. Notably, Llama3.1-8B and InternLM2.5-7B improve from 31% and
28% to 40% and 39% success rates on BigCodeBench, respectively. Our work
presents a scalable approach that leverages model-generated unit tests to guide
the synthesis of high-quality code data from pre-training corpora,
demonstrating the potential for producing diverse and high-quality
post-training data at scale. All code and data will be released
(https://github.com).
