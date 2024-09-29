---
layout: publication
title: 'Taskbench: Benchmarking Large Language Models For Task Automation'
authors: Shen Yongliang, Song Kaitao, Tan Xu, Zhang Wenqi, Ren Kan, Yuan Siyu, Lu Weiming, Li Dongsheng, Zhuang Yueting
conference: "Arxiv"
year: 2023
bibkey: shen2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18760"}
tags: ['Agent', 'Agentic', 'Tools']
---
Recently the incredible progress of large language models (LLMs) has ignited the spark of task automation which decomposes the complex tasks described by user instructions into sub-tasks and invokes external tools to execute them and plays a central role in autonomous agents. However there lacks a systematic and standardized benchmark to foster the development of LLMs in task automation. To this end we introduce TaskBench to evaluate the capability of LLMs in task automation. Specifically task automation can be formulated into three critical stages task decomposition tool invocation and parameter prediction to fulfill user intent. This complexity makes data collection and evaluation more challenging compared to common NLP tasks. To generate high-quality evaluation datasets we introduce the concept of Tool Graph to represent the decomposed tasks in user intent and adopt a back-instruct method to simulate user instruction and annotations. Furthermore we propose TaskEval to evaluate the capability of LLMs from different aspects including task decomposition tool invocation and parameter prediction. Experimental results demonstrate that TaskBench can effectively reflects the capability of LLMs in task automation. Benefiting from the mixture of automated data construction and human verification TaskBench achieves a high consistency compared to the human evaluation which can be utilized as a comprehensive and faithful benchmark for LLM-based autonomous agents.
