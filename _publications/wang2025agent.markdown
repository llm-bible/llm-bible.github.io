---
layout: publication
title: 'Codevisionary: An Agent-based Framework For Evaluating Large Language Models In Code Generation'
authors: Xinchen Wang, Pengfei Gao, Chao Peng, Ruida Hu, Cuiyun Gao
conference: "Arxiv"
year: 2025
bibkey: wang2025agent
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.13472'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/CodeVisionary'}
tags: ['Attention Mechanism', 'Agentic', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Applications', 'Reinforcement Learning']
---
Large language models (LLMs) have demonstrated strong capabilities in code
generation, underscoring the critical need for rigorous and comprehensive
evaluation. Existing evaluation approaches fall into three categories,
including human-centered, metric-based, and LLM-based. Considering that
human-centered approaches are labour-intensive and metric-based ones overly
rely on reference answers, LLM-based approaches are gaining increasing
attention due to their stronger contextual understanding capabilities and
superior efficiency. However, the performance of LLM-based approaches remains
limited due to: (1) lack of multisource domain knowledge, and (2) insufficient
comprehension of complex code.
  To mitigate the limitations, we propose CodeVisionary, the first LLM-based
agent framework for evaluating LLMs in code generation. CodeVisionary consists
of two stages: (1) Multiscore knowledge analysis stage, which aims to gather
multisource and comprehensive domain knowledge by formulating and executing a
stepwise evaluation plan. (2) Negotiation-based scoring stage, which involves
multiple judges engaging in discussions to better comprehend the complex code
and reach a consensus on the evaluation score. Extensive experiments
demonstrate that CodeVisionary achieves the best performance for evaluating
LLMs in code generation, outperforming the best baseline methods with average
improvements of 0.202, 0.139, and 0.117 in Pearson, Spearman, and Kendall-Tau
coefficients, respectively. Besides, CodeVisionary provides detailed evaluation
reports, which assist developers in identifying shortcomings and making
improvements. The resources of CodeVisionary are available at
https://anonymous.4open.science/r/CodeVisionary.
