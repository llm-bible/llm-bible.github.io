---
layout: publication
title: 'Eliminating Reasoning Via Inferring With Planning: A New Framework To Guide Llms'' Non-linear Thinking'
authors: Yongqi Tong, Yifan Wang, Dawei Li, Sizhe Wang, Zi Lin, Simeng Han, Jingbo Shang
conference: "Arxiv"
year: 2023
bibkey: tong2023eliminating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.12342"}
tags: ['Prompting', 'Tools', 'Reinforcement Learning']
---
Chain-of-Thought(CoT) prompting and its variants explore equipping large
language models (LLMs) with high-level reasoning abilities by emulating
human-like linear cognition and logic. However, the human mind is complicated
and mixed with both linear and nonlinear thinking. In this work, we propose
\textbf\{I\}nferential \textbf\{E\}xclusion \textbf\{P\}rompting (IEP), a novel
prompting that combines the principles of elimination and inference in order to
guide LLMs to think non-linearly. IEP guides LLMs to plan and then utilize
Natural Language Inference (NLI) to deduce each possible solution's entailment
relation with context, commonsense, or facts, therefore yielding a broader
perspective by thinking back for inferring. This forward planning and backward
eliminating process allows IEP to better simulate the complex human thinking
processes compared to other CoT-based methods, which only reflect linear
cognitive processes. We conducted a series of empirical studies and have
corroborated that IEP consistently outperforms CoT across various tasks.
Additionally, we observe that integrating IEP and CoT further improves the
LLMs' performance on certain tasks, highlighting the necessity of equipping
LLMs with mixed logic processes. Moreover, to better evaluate comprehensive
features inherent in human logic, we introduce \textbf\{M\}ental-\textbf\{A\}bility
\textbf\{R\}easoning \textbf\{B\}enchmark (MARB). The benchmark comprises six novel
subtasks with a total of 9,115 questions, among which 1,685 are developed with
hand-crafted rationale references. We believe both \textsc\{IEP\} and
\textsc\{MARB\} can serve as a promising direction for unveiling LLMs' logic and
verbal reasoning abilities and drive further advancements. \textsc\{MARB\} will
be available at ~\texttt\{anonymity link\} soon.
