---
layout: publication
title: 'Steptool: Enhancing Multi-step Tool Usage In Llms Through Step-grained Reinforcement Learning'
authors: Yuanqing Yu, Zhefan Wang, Weizhi Ma, Shuai Wang, Chuhan Wu, Zhiqiang Guo, Min Zhang
conference: "Arxiv"
year: 2024
bibkey: yu2024enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.07745'}
tags: ['Agentic', 'Language Modeling', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Despite powerful text generation capabilities, large language models (LLMs)
still need to learn how to utilize external tools to solve complex tasks, a
process known as tool learning. Existing methods primarily rely on supervised
fine-tuning to enhance tool-use capabilities, treating tool learning as a
text-generation task while overlooking the decision-making complexities
inherent in multi-step contexts. In this work, we propose modeling tool
learning as a dynamic decision-making task and introduce StepTool, a novel
step-grained reinforcement learning framework that enhances the multi-step tool
use capabilities of LLMs. StepTool consists of two main components:
Step-grained Reward Shaping, which assigns rewards at each tool interaction
based on the success of tool invocation and its contribution to the task; and
Step-grained Optimization, which uses policy gradient methods to optimize the
model in a multi-step manner. Experimental results demonstrate that StepTool
significantly outperforms existing methods in multi-step, tool-based tasks,
offering a robust solution for tool learning.
