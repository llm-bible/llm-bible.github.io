---
layout: publication
title: 'Uncovering Factor Level Preferences To Improve Human-model Alignment'
authors: Juhyun Oh, Eunsu Kim, Jiseon Kim, Wenda Xu, Inha Cha, William Yang Wang, Alice Oh
conference: "Arxiv"
year: 2024
bibkey: oh2024uncovering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.06965'}
tags: ['Interpretability and Explainability', 'RAG', 'Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability']
---
Despite advancements in Large Language Model (LLM) alignment, understanding
the reasons behind LLM preferences remains crucial for bridging the gap between
desired and actual behavior. LLMs often exhibit biases or tendencies that
diverge from human preferences, such as favoring certain writing styles or
producing overly verbose outputs. However, current methods for evaluating
preference alignment often lack explainability, relying on coarse-grained
comparisons. To address this, we introduce PROFILE (PRObing Factors of
InfLuence for Explainability), a novel framework that uncovers and quantifies
the influence of specific factors driving preferences. PROFILE's factor level
analysis explains the 'why' behind human-model alignment and misalignment,
offering insights into the direction of model improvement. We apply PROFILE to
analyze human and LLM preferences across three tasks: summarization, helpful
response generation, and document-based question-answering. Our factor level
analysis reveals a substantial discrepancy between human and LLM preferences in
generation tasks, whereas LLMs show strong alignment with human preferences in
evaluation tasks. We demonstrate how leveraging factor level insights,
including addressing misaligned factors or exploiting the generation-evaluation
gap, can improve alignment with human preferences. This work underscores the
importance of explainable preference analysis and highlights PROFILE's
potential to provide valuable training signals, driving further improvements in
human-model alignment.
