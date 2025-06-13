---
layout: publication
title: 'Rocketeval: Efficient Automated LLM Evaluation Via Grading Checklist'
authors: Tianjun Wei, Wei Wen, Ruizhi Qiao, Xing Sun, Jianghong Ma
conference: "Arxiv"
year: 2025
bibkey: wei2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.05142'}
  - {name: "Code", url: 'https://github.com/Joinn99/RocketEval-ICLR'}
tags: ['Has Code', 'RAG', 'Security', 'Model Architecture', 'GPT', 'Ethics and Bias', 'ICLR']
---
Evaluating large language models (LLMs) in diverse and challenging scenarios
is essential to align them with human preferences. To mitigate the prohibitive
costs associated with human evaluations, utilizing a powerful LLM as a judge
has emerged as a favored approach. Nevertheless, this methodology encounters
several challenges, including substantial expenses, concerns regarding privacy
and security, and reproducibility. In this paper, we propose a straightforward,
replicable, and accurate automated evaluation method by leveraging a
lightweight LLM as the judge, named RocketEval. Initially, we identify that the
performance disparity between lightweight and powerful LLMs in evaluation tasks
primarily stems from their ability to conduct comprehensive analyses, which is
not easily enhanced through techniques such as chain-of-thought reasoning. By
reframing the evaluation task as a multi-faceted Q&A using an instance-specific
checklist, we demonstrate that the limited judgment accuracy of lightweight
LLMs is largely attributes to high uncertainty and positional bias. To address
these challenges, we introduce an automated evaluation process grounded in
checklist grading, which is designed to accommodate a variety of scenarios and
questions. This process encompasses the creation of checklists, the grading of
these checklists by lightweight LLMs, and the reweighting of checklist items to
align with the supervised annotations. Our experiments carried out on the
automated evaluation benchmarks, MT-Bench and WildBench datasets, reveal that
RocketEval, when using Gemma-2-2B as the judge, achieves a high correlation
(0.965) with human preferences, which is comparable to GPT-4o. Moreover,
RocketEval provides a cost reduction exceeding 50-fold for large-scale
evaluation and comparison scenarios. Our code is available at
https://github.com/Joinn99/RocketEval-ICLR .
