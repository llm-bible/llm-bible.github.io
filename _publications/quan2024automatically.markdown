---
layout: publication
title: Automatically Generating Numerous Context-driven SFT Data For Llms Across Diverse Granularity
authors: Quan Shanghaoran
conference: "Arxiv"
year: 2024
bibkey: quan2024automatically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16579"}
  - {name: "Code", url: "https://github.com/quanshr/AugCon"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Training Techniques']
---
Constructing high-quality query-response pairs from custom corpus is crucial for supervised fine-tuning (SFT) large language models (LLMs) in many applications like creating domain-specific AI assistants or roleplaying agents. However sourcing this data through human annotation is costly and existing automated methods often fail to capture the diverse range of contextual granularity and tend to produce homogeneous data. To tackle these issues we introduce a novel method named AugCon capable of automatically generating context-driven SFT data across multiple levels of granularity with high diversity quality and fidelity. AugCon begins by generating queries using the Context-Split-Tree (CST) an innovative approach for recursively deriving queries and splitting context to cover full granularity. Then we train a scorer through contrastive learning to collaborate with CST to rank and refine queries. Finally a synergistic integration of self-alignment and self-improving is introduced to obtain high-fidelity responses. Extensive experiments are conducted incorporating both human and automatic evaluations encompassing a test scenario and four widely-used benchmarks in English and Chinese. The results highlight the significant advantages of AugCon in producing high diversity quality and fidelity SFT data against several state-of-the-art methods. All of our code dataset and fine-tuned model will be available at https://github.com/quanshr/AugCon.
