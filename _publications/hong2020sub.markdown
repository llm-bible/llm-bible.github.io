---
layout: publication
title: 'Sub-instruction Aware Vision-and-language Navigation'
authors: Yicong Hong, Cristian Rodriguez-opazo, Qi Wu, Stephen Gould
conference: "Arxiv"
year: 2020
citations: 50
bibkey: hong2020sub
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2004.02707'}
  - {name: "Code", url: 'https://github.com/YicongHong/Fine-Grained-R2R'}
tags: ['Attention Mechanism', 'Agentic', 'Has Code', 'Training Techniques', 'Model Architecture']
---
Vision-and-language navigation requires an agent to navigate through a real
3D environment following natural language instructions. Despite significant
advances, few previous works are able to fully utilize the strong
correspondence between the visual and textual sequences. Meanwhile, due to the
lack of intermediate supervision, the agent's performance at following each
part of the instruction cannot be assessed during navigation. In this work, we
focus on the granularity of the visual and language sequences as well as the
traceability of agents through the completion of an instruction. We provide
agents with fine-grained annotations during training and find that they are
able to follow the instruction better and have a higher chance of reaching the
target at test time. We enrich the benchmark dataset Room-to-Room (R2R) with
sub-instructions and their corresponding paths. To make use of this data, we
propose effective sub-instruction attention and shifting modules that select
and attend to a single sub-instruction at each time-step. We implement our
sub-instruction modules in four state-of-the-art agents, compare with their
baseline models, and show that our proposed method improves the performance of
all four agents.
  We release the Fine-Grained R2R dataset (FGR2R) and the code at
https://github.com/YicongHong/Fine-Grained-R2R.
