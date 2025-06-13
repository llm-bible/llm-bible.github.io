---
layout: publication
title: 'SCORE: Systematic Consistency And Robustness Evaluation For Large Language Models'
authors: Grigor Nalbandyan, Rima Shahbazyan, Evelina Bakhturina
conference: "Arxiv"
year: 2025
bibkey: nalbandyan2025systematic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.00137'}
tags: ['Security', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Typical evaluations of Large Language Models (LLMs) report a single metric
per dataset, often representing the model's best-case performance under
carefully selected settings. Unfortunately, this approach overlooks model
robustness and reliability in real-world applications. For instance, simple
paraphrasing of prompts on the MMLU-Pro dataset causes accuracy fluctuations of
up to 10%, while reordering answer choices in the AGIEval dataset results in
accuracy differences of up to 6.1%. While some studies discuss issues with LLM
robustness, there is no unified or centralized framework for evaluating the
robustness of language models. To address this gap and consolidate existing
research on model robustness, we present SCORE (\\(\mathbf\{S\}\\)ystematic
\\(\mathbf\{CO\}\\)nsistency and \\(\mathbf\{R\}\\)obustness \\(\mathbf\{E\}\\)valuation), a
comprehensive framework for non-adversarial evaluation of LLMs. The SCORE
framework evaluates models by repeatedly testing them on the same benchmarks in
various setups to give a realistic estimate of their accuracy and consistency.
We release the code publicly and start an LLM robustness leaderboard to
facilitate further development and research.
