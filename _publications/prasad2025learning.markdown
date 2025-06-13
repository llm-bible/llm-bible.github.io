---
layout: publication
title: 'Learning To Generate Unit Tests For Automated Debugging'
authors: Archiki Prasad, Elias Stengel-eskin, Justin Chih-yao Chen, Zaid Khan, Mohit Bansal
conference: "Arxiv"
year: 2025
bibkey: prasad2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.01619'}
tags: ['Reinforcement Learning']
---
Unit tests (UTs) play an instrumental role in assessing code correctness as
well as providing feedback to large language models (LLMs), motivating
automated test generation. However, we uncover a trade-off between generating
unit test inputs that reveal errors when given a faulty code and correctly
predicting the unit test output without access to the gold solution. To address
this trade-off, we propose UTGen, which teaches LLMs to generate unit test
inputs that reveal errors along with their correct expected outputs based on
task descriptions. Since model-generated tests can provide noisy signals (e.g.,
from incorrectly predicted outputs), we propose UTDebug that (i) scales UTGen
via test-time compute to improve UT output prediction, and (ii) validates and
backtracks edits based on multiple generated UTs to avoid overfitting, and
helps LLMs debug effectively. We show that UTGen outperforms other LLM-based
baselines by 7.59% based on a metric measuring the presence of both
error-revealing UT inputs and correct UT outputs. When used with UTDebug, we
find that feedback from UTGen's unit tests improves pass@1 accuracy of Qwen2.5
32B on HumanEvalFix and our own harder debugging split of MBPP+ by over 3.17%
and 12.35% (respectively) over other LLM-based UT generation baselines. Lastly,
we demonstrate that UTGen is a better judge for code correctness, outperforming
a state-of-the-art trained 8B reward model by 4.43% on HumanEval+ with
best-of-10 sampling using Qwen2.5 7B.
