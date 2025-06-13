---
layout: publication
title: 'Llm-rankfusion: Mitigating Intrinsic Inconsistency In Llm-based Ranking'
authors: Yifan Zeng, Ojas Tendolkar, Raymond Baartmans, Qingyun Wu, Lizhong Chen, Huazheng Wang
conference: "Arxiv"
year: 2024
bibkey: zeng2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00231"}
  - {name: "Code", url: "https://github.com/XHMY/LLM-RankFusion}{https://github.com/XHMY/LLM-RankFusion"}
tags: ['Tools', 'Reinforcement Learning', 'Merging', 'Has Code', 'Prompting', 'Applications']
---
Ranking passages by prompting a large language model (LLM) can achieve
promising performance in modern information retrieval (IR) systems. A common
approach to sort the ranking list is by prompting LLMs for a pairwise or
setwise comparison which often relies on sorting algorithms. However,
sorting-based methods require consistent comparisons to correctly sort the
passages, which we show that LLMs often violate. We identify two kinds of
intrinsic inconsistency in LLM-based pairwise comparisons: order inconsistency
which leads to conflicting results when switching the passage order, and
transitive inconsistency which leads to non-transitive triads among all
preference pairs. Our study of these inconsistencies is relevant for
understanding and improving the stability of any ranking scheme based on
relative preferences. In this paper, we propose LLM-RankFusion, an LLM-based
ranking framework that mitigates these inconsistencies and produces a robust
ranking list. LLM-RankFusion mitigates order inconsistency using in-context
learning (ICL) to demonstrate order-agnostic comparisons and calibration to
estimate the underlying preference probability between two passages. We then
address transitive inconsistency by aggregating the ranking results from
multiple rankers. In our experiments, we empirically show that LLM-RankFusion
can significantly reduce inconsistent comparison results, improving the ranking
quality by making the final ranking list more robust. Our code is available at
\href\{https://github.com/XHMY/LLM-RankFusion\}\{https://github.com/XHMY/LLM-RankFusion\}
