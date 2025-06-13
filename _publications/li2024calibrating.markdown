---
layout: publication
title: 'Calibraeval: Calibrating Prediction Distribution To Mitigate Selection Bias In Llms-as-judges'
authors: Haitao Li, Junjie Chen, Qingyao Ai, Zhumin Chu, Yujia Zhou, Qian Dong, Yiqun Liu
conference: "Arxiv"
year: 2024
bibkey: li2024calibrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15393"}
tags: ['Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'RAG', 'Bias Mitigation', 'Model Architecture', 'Attention Mechanism', 'Fairness']
---
The use of large language models (LLMs) as automated evaluation tools to
assess the quality of generated natural language, known as LLMs-as-Judges, has
demonstrated promising capabilities and is rapidly gaining widespread
attention. However, when applied to pairwise comparisons of candidate
responses, LLM-based evaluators often exhibit selection bias. Specifically,
their judgments may become inconsistent when the option positions or ID tokens
are swapped, compromising the effectiveness and fairness of the evaluation
result. To address this challenge, we introduce CalibraEval, a novel label-free
method for mitigating selection bias during inference. Specifically,
CalibraEval reformulates debiasing as an optimization task aimed at adjusting
observed prediction distributions to align with unbiased prediction
distributions. To solve this optimization problem, we propose a non-parametric
order-preserving algorithm (NOA). This algorithm leverages the partial order
relationships between model prediction distributions, thereby eliminating the
need for explicit labels and precise mathematical function modeling.Empirical
evaluations of LLMs in multiple representative benchmarks demonstrate that
CalibraEval effectively mitigates selection bias and improves performance
compared to existing debiasing methods. This work marks a step toward building
more robust and unbiased automated evaluation frameworks, paving the way for
improved reliability in AI-driven assessments
