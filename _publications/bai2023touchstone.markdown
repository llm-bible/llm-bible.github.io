---
layout: publication
title: Touchstone Evaluating Vision-language Models By Language Models
authors: Bai Shuai, Yang Shusheng, Bai Jinze, Wang Peng, Zhang Xingxuan, Lin Junyang, Wang Xinggang, Zhou Chang, Zhou Jingren
conference: "Arxiv"
year: 2023
bibkey: bai2023touchstone
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.16890"}
  - {name: "Code", url: "https://github.com/OFA-Sys/TouchStone"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large vision-language models (LVLMs) have recently witnessed rapid advancements exhibiting a remarkable capacity for perceiving understanding and processing visual information by connecting visual receptor with large language models (LLMs). However current assessments mainly focus on recognizing and reasoning abilities lacking direct evaluation of conversational skills and neglecting visual storytelling abilities. In this paper we propose an evaluation method that uses strong LLMs as judges to comprehensively evaluate the various abilities of LVLMs. Firstly we construct a comprehensive visual dialogue dataset TouchStone consisting of open-world images and questions covering five major categories of abilities and 27 subtasks. This dataset not only covers fundamental recognition and comprehension but also extends to literary creation. Secondly by integrating detailed image annotations we effectively transform the multimodal input content into a form understandable by LLMs. This enables us to employ advanced LLMs for directly evaluating the quality of the multimodal dialogue without requiring human intervention. Through validation we demonstrate that powerful LVLMs such as GPT-4 can effectively score dialogue quality by leveraging their textual capabilities alone aligning with human preferences. We hope our work can serve as a touchstone for LVLMs evaluation and pave the way for building stronger LVLMs. The evaluation code is available at https://github.com/OFA-Sys/TouchStone.
