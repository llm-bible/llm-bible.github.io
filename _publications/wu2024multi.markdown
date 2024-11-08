---
layout: publication
title: 'MLDT: Multi-level Decomposition For Complex Long-horizon Robotic Task Planning With Open-source Large Language Model'
authors: Wu Yike, Zhang Jiatao, Hu Nan, Tang Lanling, Qi Guilin, Shao Jun, Ren Jie, Song Wei
conference: "Arxiv"
year: 2024
bibkey: wu2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.18760"}
tags: ['RAG', 'Reinforcement Learning', 'Training Techniques']
---
In the realm of data-driven AI technology, the application of open-source
large language models (LLMs) in robotic task planning represents a significant
milestone. Recent robotic task planning methods based on open-source LLMs
typically leverage vast task planning datasets to enhance models' planning
abilities. While these methods show promise, they struggle with complex
long-horizon tasks, which require comprehending more context and generating
longer action sequences. This paper addresses this limitation by proposing
MLDT, theMulti-Level Decomposition Task planning method. This method
innovatively decomposes tasks at the goal-level, task-level, and action-level
to mitigate the challenge of complex long-horizon tasks. In order to enhance
open-source LLMs' planning abilities, we introduce a goal-sensitive corpus
generation method to create high-quality training data and conduct instruction
tuning on the generated corpus. Since the complexity of the existing datasets
is not high enough, we construct a more challenging dataset, LongTasks, to
specifically evaluate planning ability on complex long-horizon tasks. We
evaluate our method using various LLMs on four datasets in VirtualHome. Our
results demonstrate a significant performance enhancement in robotic task
planning, showcasing MLDT's effectiveness in overcoming the limitations of
existing methods based on open-source LLMs as well as its practicality in
complex, real-world scenarios.
