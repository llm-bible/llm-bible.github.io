---
layout: publication
title: 'PERC: Plan-as-query Example Retrieval For Underrepresented Code Generation'
authors: Jaeseok Yoo, Hojae Han, Youngwon Lee, Jaejin Kim, Seung-won Hwang
conference: "Arxiv"
year: 2024
bibkey: yoo2024plan
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12447'}
tags: ['Few-Shot', 'RAG', 'Security', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Code generation with large language models has shown significant promise,
especially when employing retrieval-augmented generation (RAG) with few-shot
examples. However, selecting effective examples that enhance generation quality
remains a challenging task, particularly when the target programming language
(PL) is underrepresented. In this study, we present two key findings: (1)
retrieving examples whose presented algorithmic plans can be referenced for
generating the desired behavior significantly improves generation accuracy, and
(2) converting code into pseudocode effectively captures such algorithmic
plans, enhancing retrieval quality even when the source and the target PLs are
different. Based on these findings, we propose Plan-as-query Example Retrieval
for few-shot prompting in Code generation (PERC), a novel framework that
utilizes algorithmic plans to identify and retrieve effective examples. We
validate the effectiveness of PERC through extensive experiments on the
CodeContests, HumanEval and MultiPL-E benchmarks: PERC consistently outperforms
the state-of-the-art RAG methods in code generation, both when the source and
target programming languages match or differ, highlighting its adaptability and
robustness in diverse coding environments.
