---
layout: publication
title: 'Evolving Large Language Model Assistant With Long-term Conditional Memory'
authors: Yuan Ruifeng, Sun Shichao, Wang Zili, Cao Ziqiang, Li Wenjie
conference: "Arxiv"
year: 2023
bibkey: yuan2023evolving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17257"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Tools']
---
With the rapid development of large language models, AI assistants like ChatGPT have widely entered people's works and lives. In this paper, we present an evolving large language model assistant that utilizes verbal long-term memory. It focuses on preserving the knowledge and experience from the history dialogue between the user and AI assistant, which can be applied to future dialogue for generating a better response. The model generates a set of records for each finished dialogue and stores them in the memory. In later usage, given a new user input, the model uses it to retrieve its related memory to improve the quality of the response. To find the best form of memory, we explore different ways of constructing the memory and propose a new memorizing mechanism called conditional memory to solve the problems in previous methods. We also investigate the retrieval and usage of memory in the generation process. The assistant uses GPT-4 as the backbone and we evaluate it on three constructed test datasets focusing on different abilities required by an AI assistant with long-term memory.
