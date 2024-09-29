---
layout: publication
title: QPO Query45;dependent Prompt Optimization Via Multi45;loop Offline Reinforcement Learning
authors: Kong Yilun, Mao Hangyu, Zhao Qi, Zhang Bin, Ruan Jingqing, Shen Li, Chang Yongzhe, Wang Xueqian, Zhao Rui, Tao Dacheng
conference: "Arxiv"
year: 2024
bibkey: kong2024query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10504"}
tags: ['Agentic', 'Efficiency And Optimization', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Prompt engineering has demonstrated remarkable success in enhancing the performance of large language models (LLMs) across diverse tasks. However most existing prompt optimization methods only focus on the task45;level performance overlooking the importance of query45;preferred prompts which leads to suboptimal performances. Additionally these methods rely heavily on frequent interactions with LLMs to obtain feedback for guiding the optimization process incurring substantial redundant interaction costs. In this paper we introduce Query45;dependent Prompt Optimization (QPO) which leverages multi45;loop offline reinforcement learning to iteratively fine45;tune a small pretrained language model to generate optimal prompts tailored to the input queries thus significantly improving the prompting effect on the large target LLM. We derive insights from offline prompting demonstration data which already exists in large quantities as a by45;product of benchmarking diverse prompts on open45;sourced tasks thereby circumventing the expenses of online interactions. Furthermore we continuously augment the offline dataset with the generated prompts in each loop as the prompts from the fine45;tuned model are supposed to outperform the source prompts in the original dataset. These iterative loops bootstrap the model towards generating optimal prompts. Experiments on various LLM scales and diverse NLP and math tasks demonstrate the efficacy and cost45;efficiency of our method in both zero45;shot and few45;shot scenarios.
