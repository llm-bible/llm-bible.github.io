---
layout: publication
title: The Flan Collection Designing Data And Methods For Effective Instruction Tuning
authors: Shayne Longpre, Le Hou, Tu Vu, Albert Webson, Hyung Won Chung, Yi Tay, Denny Zhou, Quoc V. Le, Barret Zoph, Jason Wei, Adam Roberts
conference: "Arxiv"
year: 2023
bibkey: longpre2023flan
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2301.13688v2"}
  - {name: "Code", url: "https://github.com/google&#45;research/FLAN/tree/main/flan/v2"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
We study the design decisions of publicly available instruction tuning methods and break down the development of Flan 2022 (Chung et al. 2022). Through careful ablation studies on the Flan Collection of tasks and methods we tease apart the effect of design decisions which enable Flan45;T5 to outperform prior work by 345;1737;+ across evaluation settings. We find task balancing and enrichment techniques are overlooked but critical to effective instruction tuning and in particular training with mixed prompt settings (zero45;shot few45;shot and chain45;of45;thought) actually yields stronger (237;+) performance in all settings. In further experiments we show Flan45;T5 requires less finetuning to converge higher and faster than T5 on single downstream tasks motivating instruction45;tuned models as more computationally45;efficient starting checkpoints for new tasks. Finally to accelerate research on instruction tuning we make the Flan 2022 collection of datasets templates and methods publicly available at https://github.com/google&#45;research/FLAN/tree/main/flan/v2.
