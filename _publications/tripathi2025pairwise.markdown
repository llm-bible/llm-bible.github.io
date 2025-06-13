---
layout: publication
title: 'Pairwise Or Pointwise? Evaluating Feedback Protocols For Bias In Llm-based Evaluation'
authors: Tuhina Tripathi, Manya Wadhwa, Greg Durrett, Scott Niekum
conference: "Arxiv"
year: 2025
bibkey: tripathi2025pairwise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14716"}
tags: ['Agentic', 'Ethics and Bias', 'Training Techniques', 'Reinforcement Learning']
---
Large Language Models (LLMs) are widely used as proxies for human labelers in
both training (Reinforcement Learning from AI Feedback) and large-scale
response evaluation (LLM-as-a-judge). Alignment and evaluation are critical
components in the development of reliable LLMs, and the choice of feedback
protocol plays a central role in both but remains understudied. In this work,
we show that the choice of feedback protocol (absolute scores versus relative
preferences) can significantly affect evaluation reliability and induce
systematic biases. In particular, we show that pairwise evaluation protocols
are more vulnerable to distracted evaluation. Generator models can exploit
spurious attributes (or distractor features) favored by the LLM judge,
resulting in inflated scores for lower-quality outputs and misleading training
signals. We find that absolute scoring is more robust to such manipulation,
producing judgments that better reflect response quality and are less
influenced by distractor features. Our results demonstrate that generator
models can flip preferences by embedding distractor features, skewing
LLM-as-a-judge comparisons and leading to inaccurate conclusions about model
quality in benchmark evaluations. Pairwise preferences flip in about 35% of the
cases, compared to only 9% for absolute scores. We offer recommendations for
choosing feedback protocols based on dataset characteristics and evaluation
objectives.
