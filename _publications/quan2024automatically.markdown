---
layout: publication
title: Automatically Generating Numerous Context45;driven SFT Data For Llms Across Diverse Granularity
authors: Quan Shanghaoran
conference: "Arxiv"
year: 2024
bibkey: quan2024automatically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16579"}
  - {name: "Code", url: "https://github.com/quanshr/AugCon"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'Has Code', 'Pretraining Methods']
---
Constructing high45;quality query45;response pairs from custom corpus is crucial for supervised fine45;tuning (SFT) large language models (LLMs) in many applications like creating domain45;specific AI assistants or roleplaying agents. However sourcing this data through human annotation is costly and existing automated methods often fail to capture the diverse range of contextual granularity and tend to produce homogeneous data. To tackle these issues we introduce a novel method named AugCon capable of automatically generating context45;driven SFT data across multiple levels of granularity with high diversity quality and fidelity. AugCon begins by generating queries using the Context45;Split45;Tree (CST) an innovative approach for recursively deriving queries and splitting context to cover full granularity. Then we train a scorer through contrastive learning to collaborate with CST to rank and refine queries. Finally a synergistic integration of self45;alignment and self45;improving is introduced to obtain high45;fidelity responses. Extensive experiments are conducted incorporating both human and automatic evaluations encompassing a test scenario and four widely45;used benchmarks in English and Chinese. The results highlight the significant advantages of AugCon in producing high diversity quality and fidelity SFT data against several state45;of45;the45;art methods. All of our code dataset and fine45;tuned model will be available at https://github.com/quanshr/AugCon.
