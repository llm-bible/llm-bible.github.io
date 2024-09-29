---
layout: publication
title: RLSF Reinforcement Learning Via Symbolic Feedback
authors: Jha Piyush, Jana Prithwish, Arora Arnav, Ganesh Vijay
conference: "Arxiv"
year: 2024
bibkey: jha2024reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16661"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
In recent years large language models (LLMs) have had a dramatic impact on various sub-fields of AI most notably on natural language understanding tasks. However there is widespread agreement that the logical reasoning capabilities of contemporary LLMs are at best fragmentary (i.e. may work well on some problem instances but fail dramatically on others). While traditional LLM fine-tuning approaches (e.g. those that use human feedback) do address this problem to some degree they suffer from many issues including unsound black-box reward models difficulties in collecting preference data and sparse scalar reward values. To address these challenges we propose a new training/fine-tuning paradigm we refer to as Reinforcement Learning via Symbolic Feedback (RLSF) which is aimed at enhancing the reasoning capabilities of LLMs. In the RLSF setting the LLM that is being trained/fine-tuned is considered as the RL agent while the environment is allowed access to reasoning or domain knowledge tools (e.g. solvers algebra systems). Crucially in RLSF these reasoning tools can provide feedback to the LLMs via poly-sized certificates (e.g. proofs) that characterize errors in the LLM-generated object with respect to some correctness specification. The ability of RLSF-based training/fine-tuning to leverage certificate-generating symbolic tools enables sound fine-grained (token-level) reward signals to LLMs and thus addresses the limitations of traditional reward models mentioned above. Via extensive evaluations we show that our RLSF-based fine-tuning of LLMs outperforms traditional approaches on two different applications namely program synthesis from natural language pseudo-code to programming language (C++) and solving the Game of 24.
