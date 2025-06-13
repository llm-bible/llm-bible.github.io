---
layout: publication
title: 'Reife: Re-evaluating Instruction-following Evaluation'
authors: Yixin Liu, Kejian Shi, Alexander R. Fabbri, Yilun Zhao, Peifeng Wang, Chien-sheng Wu, Shafiq Joty, Arman Cohan
conference: "Arxiv"
year: 2024
bibkey: liu2024re
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.07069'}
tags: ['Reinforcement Learning', 'Security']
---
The automatic evaluation of instruction following typically involves using
large language models (LLMs) to assess response quality. However, there is a
lack of comprehensive evaluation of these LLM-based evaluators across two
dimensions: the base LLMs and the evaluation protocols. Therefore, we present a
thorough meta-evaluation of instruction following, including 25 base LLMs and
15 recently proposed evaluation protocols, on 4 human-annotated datasets,
assessing the evaluation accuracy of the LLM-evaluators. Our evaluation allows
us to identify the best-performing base LLMs and evaluation protocols with a
high degree of robustness. Moreover, our large-scale evaluation reveals: (1)
Base LLM performance ranking remains largely consistent across evaluation
protocols, with less capable LLMs showing greater improvement from protocol
enhancements; (2) Robust evaluation of evaluation protocols requires many base
LLMs with varying capability levels, as protocol effectiveness can depend on
the base LLM used; (3) Evaluation results on different datasets are not always
consistent, so a rigorous evaluation requires multiple datasets with
distinctive features. We release our meta-evaluation suite ReIFE, which
provides the codebase and evaluation result collection for more than 500
LLM-evaluator configurations, to support future research in
instruction-following evaluation.
