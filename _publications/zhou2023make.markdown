---
layout: publication
title: 'Don''t Make Your LLM An Evaluation Benchmark Cheater'
authors: Kun Zhou, Yutao Zhu, Zhipeng Chen, Wentong Chen, Wayne Xin Zhao, Xu Chen, Yankai Lin, Ji-rong Wen, Jiawei Han
conference: "Arxiv"
year: 2023
bibkey: zhou2023make
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.01964"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pre-Training', 'Attention Mechanism']
---
Large language models~(LLMs) have greatly advanced the frontiers of
artificial intelligence, attaining remarkable improvement in model capacity. To
assess the model performance, a typical approach is to construct evaluation
benchmarks for measuring the ability level of LLMs in different aspects.
Despite that a number of high-quality benchmarks have been released, the
concerns about the appropriate use of these benchmarks and the fair comparison
of different models are increasingly growing. Considering these concerns, in
this paper, we discuss the potential risk and impact of inappropriately using
evaluation benchmarks and misleadingly interpreting the evaluation results.
Specially, we focus on a special issue that would lead to inappropriate
evaluation, \ie *benchmark leakage*, referring that the data related to
evaluation sets is occasionally used for model training. This phenomenon now
becomes more common since pre-training data is often prepared ahead of model
test. We conduct extensive experiments to study the effect of benchmark
leverage, and find that it can dramatically boost the evaluation results, which
would finally lead to an unreliable assessment of model performance. To improve
the use of existing evaluation benchmarks, we finally present several
guidelines for both LLM developers and benchmark maintainers. We hope this work
can draw attention to appropriate training and evaluation of LLMs.
