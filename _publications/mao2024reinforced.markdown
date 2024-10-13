---
layout: publication
title: 'Reinforced Prompt Personalization For Recommendation With Large Language Models'
authors: Mao Wenyu, Wu Jiancan, Chen Weijian, Gao Chongming, Wang Xiang, He Xiangnan
conference: "Arxiv"
year: 2024
bibkey: mao2024reinforced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17115"}
  - {name: "Code", url: "https://github.com/maowenyu-11/RPP"}
tags: ['Agentic', 'Efficiency And Optimization', 'Few Shot', 'Has Code', 'Prompting', 'RAG', 'Reinforcement Learning', 'Uncategorized']
---
Designing effective prompts can empower LLMs to understand user preferences
and provide recommendations by leveraging LLMs' intent comprehension and
knowledge utilization capabilities. However, existing research predominantly
concentrates on task-wise prompting, developing fixed prompt templates composed
of four patterns (i.e., role-playing, history records, reasoning guidance, and
output format) and applying them to all users for a given task. Although
convenient, task-wise prompting overlooks individual user differences, leading
to potential mismatches in capturing user preferences. To address it, we
introduce the concept of instance-wise prompting to personalize discrete
prompts for individual users and propose Reinforced Prompt Personalization
(RPP) to optimize the four patterns in prompts using multi-agent reinforcement
learning (MARL). To boost efficiency, RPP formulates prompt personalization as
selecting optimal sentences holistically across the four patterns, rather than
optimizing word-by-word. To ensure the quality of prompts, RPP meticulously
crafts diverse expressions for each of the four patterns, considering multiple
analytical perspectives for specific recommendation tasks. In addition to RPP,
our proposal of RPP+ aims to enhance the scalability of action space by
dynamically refining actions with LLMs throughout the iterative process. We
evaluate the effectiveness of RPP/RPP+ in ranking tasks over various datasets.
Experimental results demonstrate the superiority of RPP/RPP+ over traditional
recommender models, few-shot methods, and other prompt-based methods,
underscoring the significance of instance-wise prompting for LLMs in
recommendation tasks and validating the effectiveness of RPP/RPP+. Our code is
available at https://github.com/maowenyu-11/RPP.
