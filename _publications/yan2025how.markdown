---
layout: publication
title: 'Promote, Suppress, Iterate: How Language Models Answer One-to-many Factual Queries'
authors: Tianyi Lorena Yan, Robin Jia
conference: "Arxiv"
year: 2025
bibkey: yan2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20475"}
  - {name: "Code", url: "https://github.com/Lorenayannnnn/how-lms-answer-one-to-many-factual-queries"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
To answer one-to-many factual queries (e.g., listing cities of a country), a
language model (LM) must simultaneously recall knowledge and avoid repeating
previous answers. How are these two subtasks implemented and integrated
internally? Across multiple datasets and models, we identify a
promote-then-suppress mechanism: the model first recalls all answers, and then
suppresses previously generated ones. Specifically, LMs use both the subject
and previous answer tokens to perform knowledge recall, with attention
propagating subject information and MLPs promoting the answers. Then, attention
attends to and suppresses previous answer tokens, while MLPs amplify the
suppression signal. Our mechanism is corroborated by extensive experimental
evidence: in addition to using early decoding and causal tracing, we analyze
how components use different tokens by introducing both Token Lens, which
decodes aggregated attention updates from specified tokens, and a knockout
method that analyzes changes in MLP outputs after removing attention to
specified tokens. Overall, we provide new insights into how LMs' internal
components interact with different input tokens to support complex factual
recall. Code is available at
https://github.com/Lorenayannnnn/how-lms-answer-one-to-many-factual-queries.
