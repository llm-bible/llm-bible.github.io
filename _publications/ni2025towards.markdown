---
layout: publication
title: 'Towards Fully Exploiting LLM Internal States To Enhance Knowledge Boundary Perception'
authors: Shiyu Ni, Keping Bi, Jiafeng Guo, Lulu Yu, Baolong Bi, Xueqi Cheng
conference: "Arxiv"
year: 2025
bibkey: ni2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11677"}
tags: ['RAG', 'Applications', 'Efficiency and Optimization']
---
Large language models (LLMs) exhibit impressive performance across diverse
tasks but often struggle to accurately gauge their knowledge boundaries,
leading to confident yet incorrect responses. This paper explores leveraging
LLMs' internal states to enhance their perception of knowledge boundaries from
efficiency and risk perspectives. We investigate whether LLMs can estimate
their confidence using internal states before response generation, potentially
saving computational resources. Our experiments on datasets like Natural
Questions, HotpotQA, and MMLU reveal that LLMs demonstrate significant
pre-generation perception, which is further refined post-generation, with
perception gaps remaining stable across varying conditions. To mitigate risks
in critical domains, we introduce Consistency-based Confidence Calibration
(\\(C^3\\)), which assesses confidence consistency through question reformulation.
\\(C^3\\) significantly improves LLMs' ability to recognize their knowledge gaps,
enhancing the unknown perception rate by 5.6% on NQ and 4.9% on HotpotQA. Our
findings suggest that pre-generation confidence estimation can optimize
efficiency, while \\(C^3\\) effectively controls output risks, advancing the
reliability of LLMs in practical applications.
