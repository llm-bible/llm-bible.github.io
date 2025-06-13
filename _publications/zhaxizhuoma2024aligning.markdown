---
layout: publication
title: 'Alignbot: Aligning Vlm-powered Customized Task Planning With User Reminders Through Fine-tuning For Household Robots'
authors: Zhaxizhuoma Zhaxizhuoma, Pengan Chen, Ziniu Wu, Jiawei Sun, Dong Wang, Peng Zhou, Nieqing Cao, Yan Ding, Bin Zhao, Xuelong Li
conference: "Arxiv"
year: 2024
bibkey: zhaxizhuoma2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11905"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
This paper presents AlignBot, a novel framework designed to optimize
VLM-powered customized task planning for household robots by effectively
aligning with user reminders. In domestic settings, aligning task planning with
user reminders poses significant challenges due to the limited quantity,
diversity, and multimodal nature of the reminders. To address these challenges,
AlignBot employs a fine-tuned LLaVA-7B model, functioning as an adapter for
GPT-4o. This adapter model internalizes diverse forms of user reminders-such as
personalized preferences, corrective guidance, and contextual assistance-into
structured instruction-formatted cues that prompt GPT-4o in generating
customized task plans. Additionally, AlignBot integrates a dynamic retrieval
mechanism that selects task-relevant historical successes as prompts for
GPT-4o, further enhancing task planning accuracy. To validate the effectiveness
of AlignBot, experiments are conducted in real-world household environments,
which are constructed within the laboratory to replicate typical household
settings. A multimodal dataset with over 1,500 entries derived from volunteer
reminders is used for training and evaluation. The results demonstrate that
AlignBot significantly improves customized task planning, outperforming
existing LLM- and VLM-powered planners by interpreting and aligning with user
reminders, achieving 86.8% success rate compared to the vanilla GPT-4o baseline
at 21.6%, reflecting a 65% improvement and over four times greater
effectiveness. Supplementary materials are available at:
https://yding25.com/AlignBot/
