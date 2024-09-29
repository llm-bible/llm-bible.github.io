---
layout: publication
title: MMC Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning
authors: Liu Fuxiao, Wang Xiaoyang, Yao Wenlin, Chen Jianshu, Song Kaiqiang, Cho Sangwoo, Yacoob Yaser, Yu Dong
conference: "Arxiv"
year: 2023
bibkey: liu2023mmc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10774"}
  - {name: "Code", url: "https://github.com/FuxiaoLiu/MMC"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'RAG', 'Reinforcement Learning', 'Tools']
---
With the rapid development of large language models (LLMs) and their integration into large multimodal models (LMMs) there has been impressive progress in zero-shot completion of user-oriented vision-language tasks. However a gap remains in the domain of chart image understanding due to the distinct abstract components in charts. To address this we introduce a large-scale MultiModal Chart Instruction (textbfMMC-Instruction) dataset comprising 600k instances supporting diverse tasks and chart types. Leveraging this data we develop MultiModal Chart Assistant (textbfMMCA) an LMM that achieves state-of-the-art performance on existing chart QA benchmarks. Recognizing the need for a comprehensive evaluation of LMM chart understanding we also propose a MultiModal Chart Benchmark (textbfMMC-Benchmark) a comprehensive human-annotated benchmark with nine distinct tasks evaluating reasoning capabilities over charts. Extensive experiments on MMC-Benchmark reveal the limitations of existing LMMs on correctly interpreting charts even for the most recent GPT-4V model. Our work provides an instruction-tuning methodology and benchmark to advance multimodal understanding of charts. Code and data are available at https://github.com/FuxiaoLiu/MMC.
