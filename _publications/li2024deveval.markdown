---
layout: publication
title: Deveval Evaluating Code Generation In Practical Software Projects
authors: Li Jia, Li Ge, Zhao Yunfei, Li Yongmin, Jin Zhi, Zhu Hao, Liu Huanyu, Liu Kaibo, Wang Lecheng, Fang Zheng, Wang Lanshen, Ding Jiazheng, Zhang Xuanming, Dong Yihong, Zhu Yuqi, Gu Bin, Yang Mengfei
conference: "Arxiv"
year: 2024
bibkey: li2024deveval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06401"}
tags: ['Applications', 'GPT', 'Model Architecture']
---
How to evaluate Large Language Models (LLMs) in code generation is an open question. Many benchmarks have been proposed but are inconsistent with practical software projects e.g. unreal program distributions insufficient dependencies and small-scale project contexts. Thus the capabilities of LLMs in practical projects are still unclear. In this paper we propose a new benchmark named DevEval aligned with Developers experiences in practical projects. DevEval is collected through a rigorous pipeline containing 2690 samples from 119 practical projects and covering 10 domains. Compared to previous benchmarks DevEval aligns to practical projects in multiple dimensions e.g. real program distributions sufficient dependencies and enough-scale project contexts. We assess five popular LLMs on DevEval (e.g. gpt-4 gpt-3.5-turbo CodeLLaMa and StarCoder) and reveal their actual abilities in code generation. For instance the highest Pass35;64;1 of gpt-3.5-turbo only is 42 in our experiments. We also discuss the challenges and future directions of code generation in practical projects. We open-source DevEval and hope it can facilitate the development of code generation in practical projects.
