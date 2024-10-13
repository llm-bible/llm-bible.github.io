---
layout: publication
title: 'Self-playing Adversarial Language Game Enhances LLM Reasoning'
authors: Cheng Pengyu, Hu Tianhao, Xu Han, Zhang Zhisong, Dai Yong, Han Lei, Du Nan
conference: "Arxiv"
year: 2024
bibkey: cheng2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10642"}
  - {name: "Code", url: "https://github.com/Linear95/SPAG"}
tags: ['Agentic', 'Has Code', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
We explore the self-play training procedure of large language models (LLMs)
in a two-player adversarial language game called Adversarial Taboo. In this
game, an attacker and a defender communicate around a target word only visible
to the attacker. The attacker aims to induce the defender to speak the target
word unconsciously, while the defender tries to infer the target word from the
attacker's utterances. To win the game, both players should have sufficient
knowledge about the target word and high-level reasoning ability to infer and
express in this information-reserved conversation. Hence, we are curious about
whether LLMs' reasoning ability can be further enhanced by self-play in this
adversarial language game (SPAG). With this goal, we select several open-source
LLMs and let each act as the attacker and play with a copy of itself as the
defender on an extensive range of target words. Through reinforcement learning
on the game outcomes, we observe that the LLMs' performances uniformly improve
on a broad range of reasoning benchmarks. Furthermore, iteratively adopting
this self-play process can continuously promote LLMs' reasoning abilities. The
code is at https://github.com/Linear95/SPAG.
