---
layout: publication
title: Gpt4tools Teaching Large Language Model To Use Tools Via Self45;instruction
authors: Rui Yang, Lin Song, Yanwei Li, Sijie Zhao, Yixiao Ge, Xiu Li, Ying Shan
conference: "Arxiv"
year: 2023
bibkey: yang2023teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2305.18752v1"}
  - {name: "Code", url: "https://github.com/StevenGrove/GPT4Tools"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Tools']
---
This paper aims to efficiently enable Large Language Models (LLMs) to use multimodal tools. Advanced proprietary LLMs such as ChatGPT and GPT45;4 have shown great potential for tool usage through sophisticated prompt engineering. Nevertheless these models typically rely on prohibitive computational costs and publicly inaccessible data. To address these challenges we propose the GPT4Tools based on self45;instruct to enable open45;source LLMs such as LLaMA and OPT to use tools. It generates an instruction45;following dataset by prompting an advanced teacher with various multi45;modal contexts. By using the Low45;Rank Adaptation (LoRA) optimization our approach facilitates the open45;source LLMs to solve a range of visual problems including visual comprehension and image generation. Moreover we provide a benchmark to evaluate the ability of LLMs to use tools which is performed in both zero45;shot and fine45;tuning ways. Extensive experiments demonstrate the effectiveness of our method on various language models which not only significantly improves the accuracy of invoking seen tools but also enables the zero45;shot capacity for unseen tools. The code and demo are available at https://github.com/StevenGrove/GPT4Tools.
