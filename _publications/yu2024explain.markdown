---
layout: publication
title: 'Explain Then Rank: Scale Calibration Of Neural Rankers Using Natural Language Explanations From Llms'
authors: Puxuan Yu, Daniel Cohen, Hemank Lamba, Joel Tetreault, Alex Jaimes
conference: "Arxiv"
year: 2024
bibkey: yu2024explain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.12276'}
tags: ['Reinforcement Learning', 'Interpretability and Explainability', 'TACL', 'ACL']
---
In search settings, calibrating the scores during the ranking process to
quantities such as click-through rates or relevance levels enhances a system's
usefulness and trustworthiness for downstream users. While previous research
has improved this notion of calibration for low complexity learning-to-rank
models, the larger data demands and parameter count specific to modern neural
text rankers produce unique obstacles that hamper the efficacy of methods
intended for the learning-to-rank setting.
  This paper proposes exploiting large language models (LLMs) to provide
relevance and uncertainty signals for these neural text rankers to produce
scale-calibrated scores through Monte Carlo sampling of natural language
explanations (NLEs). Our approach transforms the neural ranking task from
ranking textual query-document pairs to ranking corresponding synthesized NLEs.
Comprehensive experiments on two popular document ranking datasets show that
the NLE-based calibration approach consistently outperforms past calibration
methods and LLM-based methods for ranking, calibration, and query performance
prediction tasks.
