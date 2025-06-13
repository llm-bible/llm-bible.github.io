---
layout: publication
title: 'Inductive-deductive Strategy Reuse For Multi-turn Instructional Dialogues'
authors: Jiao Ou, Jiayu Wu, Che Liu, Fuzheng Zhang, Di Zhang, Kun Gai
conference: "Arxiv"
year: 2024
bibkey: ou2024inductive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11095"}
tags: ['Agentic', 'RAG']
---
Aligning large language models (LLMs) with human expectations requires
high-quality instructional dialogues, which usually require instructions that
are diverse and in-depth. Existing methods leverage two LLMs to interact for
automatic collection: one simulating a user to pose instructions, and the other
acting as a system agent to respond. However, these user simulators struggle to
model the rules behind how dialogues can pose different instructions without
explicit guidance, resulting in general instructions. In this paper, we propose
to explicitly capture the complex rules to help the user simulator pose diverse
and in-depth instruction. Specifically, we first induce high-level instruction
strategies from various real instruction dialogues serving as rules. Afterward,
different possible strategies are applied to the newly given dialogue scenario
deductively to pose various instructions. Experimental results show that our
method can generate diverse and in-depth instructions. The constructed
multi-turn instructional dialogues can outperform competitive baselines on the
downstream chat model.
