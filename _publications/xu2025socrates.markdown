---
layout: publication
title: 'Socrates Or Smartypants: Testing Logic Reasoning Capabilities Of Large Language Models With Logic Programming-based Test Oracles'
authors: Zihao Xu, Junchen Ding, Yiling Lou, Kun Zhang, Dong Gong, Yuekang Li
conference: "Arxiv"
year: 2025
bibkey: xu2025socrates
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12312"}
tags: ['ACL', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) have achieved significant progress in language
understanding and reasoning. Evaluating and analyzing their logical reasoning
abilities has therefore become essential. However, existing datasets and
benchmarks are often limited to overly simplistic, unnatural, or contextually
constrained examples. In response to the growing demand, we introduce
SmartyPat-Bench, a challenging, naturally expressed, and systematically labeled
benchmark derived from real-world high-quality Reddit posts containing subtle
logical fallacies. Unlike existing datasets and benchmarks, it provides more
detailed annotations of logical fallacies and features more diverse data. To
further scale up the study and address the limitations of manual data
collection and labeling - such as fallacy-type imbalance and labor-intensive
annotation - we introduce SmartyPat, an automated framework powered by logic
programming-based oracles. SmartyPat utilizes Prolog rules to systematically
generate logically fallacious statements, which are then refined into fluent
natural-language sentences by LLMs, ensuring precise fallacy representation.
Extensive evaluation demonstrates that SmartyPat produces fallacies comparable
in subtlety and quality to human-generated content and significantly
outperforms baseline methods. Finally, experiments reveal nuanced insights into
LLM capabilities, highlighting that while excessive reasoning steps hinder
fallacy detection accuracy, structured reasoning enhances fallacy
categorization performance.
