---
layout: publication
title: 'Lagr-seq: Language-guided Reinforcement Learning With Sample-efficient Querying'
authors: Thommen George Karimpanal, Laknath Buddhika Semage, Santu Rana, Hung Le, Truyen Tran, Sunil Gupta, Svetha Venkatesh
conference: "Arxiv"
year: 2023
bibkey: karimpanal2023lagr
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.13542'}
tags: ['Reinforcement Learning', 'Agentic', 'Training Techniques', 'Tools']
---
Large language models (LLMs) have recently demonstrated their impressive
ability to provide context-aware responses via text. This ability could
potentially be used to predict plausible solutions in sequential decision
making tasks pertaining to pattern completion. For example, by observing a
partial stack of cubes, LLMs can predict the correct sequence in which the
remaining cubes should be stacked by extrapolating the observed patterns (e.g.,
cube sizes, colors or other attributes) in the partial stack. In this work, we
introduce LaGR (Language-Guided Reinforcement learning), which uses this
predictive ability of LLMs to propose solutions to tasks that have been
partially completed by a primary reinforcement learning (RL) agent, in order to
subsequently guide the latter's training. However, as RL training is generally
not sample-efficient, deploying this approach would inherently imply that the
LLM be repeatedly queried for solutions; a process that can be expensive and
infeasible. To address this issue, we introduce SEQ (sample efficient
querying), where we simultaneously train a secondary RL agent to decide when
the LLM should be queried for solutions. Specifically, we use the quality of
the solutions emanating from the LLM as the reward to train this agent. We show
that our proposed framework LaGR-SEQ enables more efficient primary RL
training, while simultaneously minimizing the number of queries to the LLM. We
demonstrate our approach on a series of tasks and highlight the advantages of
our approach, along with its limitations and potential future research
directions.
