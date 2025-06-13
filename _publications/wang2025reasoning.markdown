---
layout: publication
title: 'Reasoning On Multiple Needles In A Haystack'
authors: Yidong Wang
conference: "Arxiv"
year: 2025
bibkey: wang2025reasoning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.04150'}
tags: ['Reinforcement Learning', 'GPT', 'Model Architecture']
---
The Needle In A Haystack (NIAH) task has been widely used to evaluate the
long-context question-answering capabilities of Large Language Models (LLMs).
However, its reliance on simple retrieval limits its effectiveness. To address
this limitation, recent studies have introduced the Multiple Needles In A
Haystack Reasoning (MNIAH-R) task, which incorporates supporting documents
(Multiple needles) of multi-hop reasoning tasks into a distracting context
(Haystack\}). Despite this advancement, existing approaches still fail to
address the issue of models providing direct answers from internal knowledge,
and they do not explain or mitigate the decline in accuracy as context length
increases. In this paper, we tackle the memory-based answering problem by
filtering out direct-answer questions, and we reveal that performance
degradation is primarily driven by the reduction in the length of the thinking
process as the input length increases. Building on this insight, we decompose
the thinking process into retrieval and reasoning stages and introduce a
reflection mechanism for multi-round extension. We also train a model using the
generated iterative thinking process, which helps mitigate the performance
degradation. Furthermore, we demonstrate the application of this
retrieval-reflection capability in mathematical reasoning scenarios, improving
GPT-4o's performance on AIME2024.
