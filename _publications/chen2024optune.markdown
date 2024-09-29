---
layout: publication
title: OPTune Efficient Online Preference Tuning
authors: Chen Lichang, Chen Jiuhai, Liu Chenxi, Kirchenbauer John, Soselia Davit, Zhu Chen, Goldstein Tom, Zhou Tianyi, Huang Heng
conference: "Arxiv"
year: 2024
bibkey: chen2024optune
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07657"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Reinforcement learning with human feedback~(RLHF) is critical for aligning Large Language Models (LLMs) with human preference. Compared to the widely studied offline version of RLHF direct preference optimization (DPO) recent works have shown that the online variants achieve even better alignment. However online alignment requires on-the-fly generation of new training data which is costly hard to parallelize and suffers from varying quality and utility. In this paper we propose a more efficient data exploration strategy for online preference tuning (OPTune) which does not rely on human-curated or pre-collected teacher responses but dynamically samples informative responses for on-policy preference alignment. During data generation OPTune only selects prompts whose (re)generated responses can potentially provide more informative and higher-quality training signals than the existing responses. In the training objective OPTune reweights each generated response (pair) by its utility in improving the alignment so that learning can be focused on the most helpful samples. Throughout our evaluations OPTuned LLMs maintain the instruction-following benefits provided by standard preference tuning whilst enjoying 1.27-1.56x faster training speed due to the efficient data exploration strategy.
