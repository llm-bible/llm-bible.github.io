---
layout: publication
title: 'Systematic Evaluation Of Long-context Llms On Financial Concepts'
authors: Lavanya Gupta, Saket Sharma, Yiyun Zhao
conference: "In Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing Industry Track Miami Florida US Association for Computational Linguistics"
year: 2024
bibkey: gupta2024systematic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.15386'}
tags: ['Reinforcement Learning', 'GPT', 'Prompting', 'Model Architecture']
---
Long-context large language models (LC LLMs) promise to increase reliability
of LLMs in real-world tasks requiring processing and understanding of long
input documents. However, this ability of LC LLMs to reliably utilize their
growing context windows remains under investigation. In this work, we evaluate
the performance of state-of-the-art GPT-4 suite of LC LLMs in solving a series
of progressively challenging tasks, as a function of factors such as context
length, task difficulty, and position of key information by creating a real
world financial news dataset. Our findings indicate that LC LLMs exhibit
brittleness at longer context lengths even for simple tasks, with performance
deteriorating sharply as task complexity increases. At longer context lengths,
these state-of-the-art models experience catastrophic failures in instruction
following resulting in degenerate outputs. Our prompt ablations also reveal
unfortunate continued sensitivity to both the placement of the task instruction
in the context window as well as minor markdown formatting. Finally, we
advocate for more rigorous evaluation of LC LLMs by employing holistic metrics
such as F1 (rather than recall) and reporting confidence intervals, thereby
ensuring robust and conclusive findings.
