---
layout: publication
title: 'Joint Evaluation Of Answer And Reasoning Consistency For Hallucination Detection In Large Reasoning Models'
authors: Changyue Wang, Weihang Su, Qingyao Ai, Yiqun Liu
conference: "Arxiv"
year: 2025
bibkey: wang2025joint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04832"}
  - {name: "Code", url: "https://github.com/bebr2/RACE"}
tags: ['Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'Has Code']
---
Large Reasoning Models (LRMs) extend large language models with explicit, multi-step reasoning traces to enhance transparency and performance on complex tasks. However, these reasoning traces can be redundant or logically inconsistent, making them a new source of hallucination that is difficult to detect. Existing hallucination detection methods focus primarily on answer-level uncertainty and often fail to detect hallucinations or logical inconsistencies arising from the model's reasoning trace. This oversight is particularly problematic for LRMs, where the explicit thinking trace is not only an important support to the model's decision-making process but also a key source of potential hallucination. To this end, we propose RACE (Reasoning and Answer Consistency Evaluation), a novel framework specifically tailored for hallucination detection in LRMs. RACE operates by extracting essential reasoning steps and computing four diagnostic signals: inter-sample consistency of reasoning traces, entropy-based answer uncertainty, semantic alignment between reasoning and answers, and internal coherence of reasoning. This joint analysis enables fine-grained hallucination detection even when the final answer appears correct. Experiments across datasets and different LLMs demonstrate that RACE outperforms existing hallucination detection baselines, offering a robust and generalizable solution for evaluating LRMs. Our code is available at: https://github.com/bebr2/RACE.
