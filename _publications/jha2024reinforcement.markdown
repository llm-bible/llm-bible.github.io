---
layout: publication
title: RLSF Reinforcement Learning Via Symbolic Feedback
authors: Jha Piyush, Jana Prithwish, Arora Arnav, Ganesh Vijay
conference: "Arxiv"
year: 2024
bibkey: jha2024reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16661"}
tags: ['Agentic', 'Applications', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
In recent years large language models (LLMs) have had a dramatic impact on various sub45;fields of AI most notably on natural language understanding tasks. However there is widespread agreement that the logical reasoning capabilities of contemporary LLMs are at best fragmentary (i.e. may work well on some problem instances but fail dramatically on others). While traditional LLM fine45;tuning approaches (e.g. those that use human feedback) do address this problem to some degree they suffer from many issues including unsound black45;box reward models difficulties in collecting preference data and sparse scalar reward values. To address these challenges we propose a new training/fine45;tuning paradigm we refer to as Reinforcement Learning via Symbolic Feedback (RLSF) which is aimed at enhancing the reasoning capabilities of LLMs. In the RLSF setting the LLM that is being trained/fine45;tuned is considered as the RL agent while the environment is allowed access to reasoning or domain knowledge tools (e.g. solvers algebra systems). Crucially in RLSF these reasoning tools can provide feedback to the LLMs via poly45;sized certificates (e.g. proofs) that characterize errors in the LLM45;generated object with respect to some correctness specification. The ability of RLSF45;based training/fine45;tuning to leverage certificate45;generating symbolic tools enables sound fine45;grained (token45;level) reward signals to LLMs and thus addresses the limitations of traditional reward models mentioned above. Via extensive evaluations we show that our RLSF45;based fine45;tuning of LLMs outperforms traditional approaches on two different applications namely program synthesis from natural language pseudo45;code to programming language (C++) and solving the Game of 24.
