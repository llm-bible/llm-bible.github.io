---
layout: publication
title: Wikitableedit: A Benchmark For Table Editing By Natural Language Instruction
authors: Li Zheng, Chen Xiang, Wan Xiaojun
conference: "Arxiv"
year: 2024
bibkey: li2024benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02962"}
tags: ['Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Tabular data as a crucial form of data representation exists in diverse formats on the Web. When confronted with complex and irregular tables manual modification becomes a laborious task. This paper investigates the performance of Large Language Models (LLMs) in the context of table editing tasks. Existing research mainly focuses on regular-shaped tables wherein instructions are used to generate code in SQL Python or Excel Office-script for manipulating the tables. Nevertheless editing tables with irregular structures particularly those containing merged cells spanning multiple rows poses a challenge when using code. To address this we introduce the WikiTableEdit dataset. Leveraging 26531 tables from the WikiSQL dataset we automatically generate natural language instructions for six distinct basic operations and the corresponding outcomes resulting in over 200000 instances. Subsequently we evaluate several representative large language models on the WikiTableEdit dataset to demonstrate the challenge of this task. The dataset will be released to the community to promote related researches.
