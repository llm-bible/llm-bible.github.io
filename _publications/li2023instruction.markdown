---
layout: publication
title: Instructcoder Instruction Tuning Large Language Models For Code Editing
authors: Li Kaixin, Hu Qisheng, Zhao Xu, Chen Hui, Xie Yuxi, Liu Tiedong, Xie Qizhe, He Junxian
conference: "Arxiv"
year: 2023
bibkey: li2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20329"}
  - {name: "Code", url: "https://github.com/qishenghu/CodeInstruct"}
tags: ['Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG']
---
Code editing encompasses a variety of pragmatic tasks that developers deal with daily. Despite its relevance and practical usefulness automatic code editing remains an underexplored area in the evolution of deep learning models partly due to data scarcity. In this work we explore the use of Large Language Models (LLMs) to edit code based on user instructions. Evaluated on a novel human45;written execution45;based benchmark dubbed EditEval we found current models often struggle to fulfill the instructions. In light of this we contribute InstructCoder the first instruction45;tuning dataset designed to adapt LLMs for general45;purpose code editing containing high45;diversity code45;editing tasks such as comment insertion code optimization and code refactoring. It consists of over 114000 instruction45;input45;output triplets and covers multiple distinct code editing scenarios. The collection process starts with filtered commit data sourced from GitHub Python repositories as seeds. Subsequently the dataset is systematically expanded through an iterative process where both seed and generated tasks are used to prompt ChatGPT for more data. Our findings reveal that open45;source LLMs fine45;tuned on InstructCoder can significantly enhance the accuracy of code edits exhibiting superior code45;editing performance matching advanced proprietary LLMs. The datasets and the source code are publicly available at https://github.com/qishenghu/CodeInstruct.
