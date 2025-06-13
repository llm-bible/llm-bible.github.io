---
layout: publication
title: 'Ugmathbench: A Diverse And Dynamic Benchmark For Undergraduate-level Mathematical Reasoning With Large Language Models'
authors: Xin Xu, Jiaxin Zhang, Tianhao Chen, Zitong Chao, Jishan Hu, Can Yang
conference: "International Conference on Learning Representations (ICLR 2025)"
year: 2025
bibkey: xu2025diverse
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.13766'}
  - {name: "Code", url: 'https://github.com/YangLabHKUST/UGMathBench'}
tags: ['RAG', 'Has Code', 'Security']
---
Large Language Models (LLMs) have made significant strides in mathematical
reasoning, underscoring the need for a comprehensive and fair evaluation of
their capabilities. However, existing benchmarks often fall short, either
lacking extensive coverage of undergraduate-level mathematical problems or
probably suffering from test-set contamination. To address these issues, we
introduce UGMathBench, a diverse and dynamic benchmark specifically designed
for evaluating undergraduate-level mathematical reasoning with LLMs.
UGMathBench comprises 5,062 problems across 16 subjects and 111 topics,
featuring 10 distinct answer types. Each problem includes three randomized
versions, with additional versions planned for release as leading open-source
LLMs become saturated in UGMathBench. Furthermore, we propose two key metrics:
effective accuracy (EAcc), which measures the percentage of correctly solved
problems across all three versions, and reasoning gap (\\(\Delta\\)), which
assesses reasoning robustness by calculating the difference between the average
accuracy across all versions and EAcc. Our extensive evaluation of 23 leading
LLMs reveals that the highest EAcc achieved is 56.3% by OpenAI-o1-mini, with
large \\(\Delta\\) values observed across different models. This highlights the
need for future research aimed at developing "large reasoning models" with high
EAcc and \\(\Delta = 0\\). We anticipate that the release of UGMathBench, along
with its detailed evaluation codes, will serve as a valuable resource to
advance the development of LLMs in solving mathematical problems. Codes and
data are available at https://github.com/YangLabHKUST/UGMathBench
