---
layout: publication
title: 'Boosting Reward Model With Preference-conditional Multi-aspect Synthetic Data Generation'
authors: Shen Jiaming, Xu Ran, Jun Yennie, Qin Zhen, Liu Tianqi, Yang Carl, Liang Yi, Baumgartner Simon, Bendersky Michael
conference: "Arxiv"
year: 2024
bibkey: shen2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16008"}
tags: ['Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Reward models (RMs) are crucial for aligning large language models (LLMs) with human preferences. They are trained using preference datasets where each example consists of one input prompt two responses and a preference label. As curating a high-quality human labeled preference dataset is both time-consuming and expensive people often rely on existing powerful LLMs for preference label generation. This can potentially introduce noise and impede RM training. In this work we present RMBoost a novel synthetic preference data generation paradigm to boost reward model quality. Unlike traditional methods which generate two responses before obtaining the preference label RMBoost first generates one response and selects a preference label followed by generating the second more (or less) preferred response conditioned on the pre-selected preference label and the first response. This approach offers two main advantages. First RMBoost reduces labeling noise since preference pairs are constructed intentionally. Second RMBoost facilitates the creation of more diverse responses by incorporating various quality aspects (e.g. helpfulness relevance completeness) into the prompts. We conduct extensive experiments across three diverse datasets and demonstrate that RMBoost outperforms other synthetic preference data generation techniques and significantly boosts the performance of four distinct reward models.
