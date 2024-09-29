---
layout: publication
title: Planning In Natural Language Improves LLM Search For Code Generation
authors: Wang Evan, Cassano Federico, Wu Catherine, Bai Yunfeng, Song Will, Nath Vaskar, Han Ziwen, Hendryx Sean, Yue Summer, Zhang Hugh
conference: "Arxiv"
year: 2024
bibkey: wang2024planning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03733"}
tags: ['Applications', 'Training Techniques']
---
While scaling training compute has led to remarkable improvements in large language models (LLMs) scaling inference compute has not yet yielded analogous gains. We hypothesize that a core missing component is a lack of diverse LLM outputs leading to inefficient search due to models repeatedly sampling highly similar yet incorrect generations. We empirically demonstrate that this lack of diversity can be mitigated by searching over candidate plans for solving a problem in natural language. Based on this insight we propose PLANSEARCH a novel search algorithm which shows strong results across HumanEval+ MBPP+ and LiveCodeBench (a contamination-free benchmark for competitive coding). PLANSEARCH generates a diverse set of observations about the problem and then uses these observations to construct plans for solving the problem. By searching over plans in natural language rather than directly over code solutions PLANSEARCH explores a significantly more diverse range of potential solutions compared to baseline search methods. Using PLANSEARCH on top of Claude 3.5 Sonnet achieves a state-of-the-art pass35;64;200 of 77.037; on LiveCodeBench outperforming both the best score achieved without search (pass35;64;1 = 41.437;) and using standard repeated sampling (pass35;64;200 = 60.637;). Finally we show that across all models search algorithms and benchmarks analyzed we can accurately predict performance gains due to search as a direct function of the diversity over generated ideas.
