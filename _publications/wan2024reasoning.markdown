---
layout: publication
title: 'Reasoning Aware Self-consistency: Leveraging Reasoning Paths For Efficient LLM Sampling'
authors: Guangya Wan, Yuqi Wu, Jie Chen, Sheng Li
conference: "Arxiv"
year: 2024
bibkey: wan2024reasoning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.17017'}
tags: ['Reinforcement Learning', 'RAG', 'Efficiency and Optimization', 'Tools']
---
Self-Consistency mitigates hallucinations in Large Language Models (LLMs) by
sampling multiple reasoning paths,but it lacks a systematic approach to
determine the optimal number of samples or select the most faithful rationale.
To address this limitation, we introduce Reasoning-Aware Self-Consistency
(RASC), a novel framework that enhances sampling efficiency and reasoning
faithfulness by dynamically evaluating both outputs and rationales. RASC
assesses the quality of reasoning and the consistency of answers for each
generated sample, using these assessments to guide early stopping decisions and
rationale selection. The framework employs criteria-based stopping and weighted
majority voting, enabling more informed choices on when to halt sampling and
which rationale to select. Our comprehensive experiments across diverse
question-answering datasets demonstrate that RASC outperforms existing methods,
reducing sample usage by approximately 70% while maintaining accuracy.
Moreover, RASC facilitates the selection of high-fidelity rationales, thereby
improving the faithfulness of LLM outputs. Our approach effectively addresses
the efficiency-accuracy trade-off in LLM reasoning tasks, offering a new
perspective for more nuanced, faithful, and effective utilization of LLMs in
resource-constrained environments.
