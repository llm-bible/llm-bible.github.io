---
layout: publication
title: 'HPSS: Heuristic Prompting Strategy Search For LLM Evaluators'
authors: Bosi Wen, Pei Ke, Yufei Sun, Cunxiang Wang, Xiaotao Gu, Jinfeng Zhou, Jie Tang, Hongning Wang, Minlie Huang
conference: "Arxiv"
year: 2025
bibkey: wen2025heuristic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13031'}
  - {name: "Code", url: 'https://github.com/thu-coai/HPSS'}
tags: ['Prompting', 'Has Code', 'Efficiency and Optimization']
---
Since the adoption of large language models (LLMs) for text evaluation has become increasingly prevalent in the field of natural language processing (NLP), a series of existing works attempt to optimize the prompts for LLM evaluators to improve their alignment with human judgment. However, their efforts are limited to optimizing individual factors of evaluation prompts, such as evaluation criteria or output formats, neglecting the combinatorial impact of multiple factors, which leads to insufficient optimization of the evaluation pipeline. Nevertheless, identifying well-behaved prompting strategies for adjusting multiple factors requires extensive enumeration. To this end, we comprehensively integrate 8 key factors for evaluation prompts and propose a novel automatic prompting strategy optimization method called Heuristic Prompting Strategy Search (HPSS). Inspired by the genetic algorithm, HPSS conducts an iterative search to find well-behaved prompting strategies for LLM evaluators. A heuristic function is employed to guide the search process, enhancing the performance of our algorithm. Extensive experiments across four evaluation tasks demonstrate the effectiveness of HPSS, consistently outperforming both human-designed evaluation prompts and existing automatic prompt optimization methods. Our code is available at https://github.com/thu-coai/HPSS.
