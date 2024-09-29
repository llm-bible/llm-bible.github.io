---
layout: publication
title: Sub45;instruction Aware Vision45;and45;language Navigation
authors: Hong Yicong, Rodriguez-opazo Cristian, Wu Qi, Gould Stephen
conference: "Arxiv"
year: 2020
bibkey: hong2020sub
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.02707"}
  - {name: "Code", url: "https://github.com/YicongHong/Fine&#45;Grained&#45;R2R"}
tags: ['Agentic', 'Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'Training Techniques']
---
Vision45;and45;language navigation requires an agent to navigate through a real 3D environment following natural language instructions. Despite significant advances few previous works are able to fully utilize the strong correspondence between the visual and textual sequences. Meanwhile due to the lack of intermediate supervision the agents performance at following each part of the instruction cannot be assessed during navigation. In this work we focus on the granularity of the visual and language sequences as well as the traceability of agents through the completion of an instruction. We provide agents with fine45;grained annotations during training and find that they are able to follow the instruction better and have a higher chance of reaching the target at test time. We enrich the benchmark dataset Room45;to45;Room (R2R) with sub45;instructions and their corresponding paths. To make use of this data we propose effective sub45;instruction attention and shifting modules that select and attend to a single sub45;instruction at each time45;step. We implement our sub45;instruction modules in four state45;of45;the45;art agents compare with their baseline models and show that our proposed method improves the performance of all four agents. We release the Fine45;Grained R2R dataset (FGR2R) and the code at https://github.com/YicongHong/Fine&#45;Grained&#45;R2R.
