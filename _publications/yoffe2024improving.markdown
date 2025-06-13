---
layout: publication
title: 'Debunc: Improving Large Language Model Agent Communication With Uncertainty Metrics'
authors: Luke Yoffe, Alfonso Amayuelas, William Yang Wang
conference: "Arxiv"
year: 2024
bibkey: yoffe2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.06426'}
  - {name: "Code", url: 'https://github.com/lukeyoffe/debunc'}
tags: ['Attention Mechanism', 'Agentic', 'Has Code', 'Transformer', 'Model Architecture', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Multi-agent debates have been introduced to improve the accuracy of Large
Language Models (LLMs) by having multiple agents discuss solutions to a problem
over several rounds of debate. However, models often generate incorrect yet
confident-sounding responses, which can mislead others. This issue arises
partly because agents do not consider how confident their peers are. To address
this, we propose DebUnc, a debate framework that uses uncertainty metrics to
assess agent confidence. Confidence is then conveyed through a modified
attention mechanism that adjusts token weights, or through textual prompts.
Evaluations across benchmarks show that attention-based methods are
particularly effective and that performance continues to improve as uncertainty
estimation becomes more reliable. The code is available at
https://github.com/lukeyoffe/debunc.
