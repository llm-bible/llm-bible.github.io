---
layout: publication
title: 'Lohoravens: A Long-horizon Language-conditioned Benchmark For Robotic Tabletop Manipulation'
authors: Shengqiang Zhang, Philipp Wicke, Lütfi Kerem Şenel, Luis Figueredo, Abdeldjallil Naceri, Sami Haddadin, Barbara Plank, Hinrich Schütze
conference: "Arxiv"
year: 2023
bibkey: zhang2023long
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.12020'}
tags: ['Reinforcement Learning', 'Agentic']
---
The convergence of embodied agents and large language models (LLMs) has
brought significant advancements to embodied instruction following.
Particularly, the strong reasoning capabilities of LLMs make it possible for
robots to perform long-horizon tasks without expensive annotated
demonstrations. However, public benchmarks for testing the long-horizon
reasoning capabilities of language-conditioned robots in various scenarios are
still missing. To fill this gap, this work focuses on the tabletop manipulation
task and releases a simulation benchmark, \textit\{LoHoRavens\}, which covers
various long-horizon reasoning aspects spanning color, size, space, arithmetics
and reference. Furthermore, there is a key modality bridging problem for
long-horizon manipulation tasks with LLMs: how to incorporate the observation
feedback during robot execution for the LLM's closed-loop planning, which is
however less studied by prior work. We investigate two methods of bridging the
modality gap: caption generation and learnable interface for incorporating
explicit and implicit observation feedback to the LLM, respectively. These
methods serve as the two baselines for our proposed benchmark. Experiments show
that both methods struggle to solve some tasks, indicating long-horizon
manipulation tasks are still challenging for current popular models. We expect
the proposed public benchmark and baselines can help the community develop
better models for long-horizon tabletop manipulation tasks.
