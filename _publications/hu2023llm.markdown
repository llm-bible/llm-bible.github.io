---
layout: publication
title: Llm45;adapters An Adapter Family For Parameter45;efficient Fine45;tuning Of Large Language Models
authors: Hu Zhiqiang, Wang Lei, Lan Yihuai, Xu Wanyu, Lim Ee-peng, Bing Lidong, Xu Xing, Poria Soujanya, Lee Roy Ka-wei
conference: "Arxiv"
year: 2023
bibkey: hu2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.01933"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools']
---
The success of large language models (LLMs) like GPT45;4 and ChatGPT has led to the development of numerous cost45;effective and accessible alternatives that are created by finetuning open45;access LLMs with task45;specific data (e.g. ChatDoctor) or instruction data (e.g. Alpaca). Among the various fine45;tuning methods adapter45;based parameter45;efficient fine45;tuning (PEFT) is undoubtedly one of the most attractive topics as it only requires fine45;tuning a few external parameters instead of the entire LLMs while achieving comparable or even better performance. To enable further research on PEFT methods of LLMs this paper presents LLM45;Adapters an easy45;to45;use framework that integrates various adapters into LLMs and can execute these adapter45;based PEFT methods of LLMs for different tasks. The framework includes state45;of45;the45;art open45;access LLMs such as LLaMA BLOOM and GPT45;J as well as widely used adapters such as Series adapters Parallel adapter Prompt45;based learning and Reparametrization45;based methods. Moreover we conduct extensive empirical studies on the impact of adapter types placement locations and hyper45;parameters to the best design for each adapter45;based methods. We evaluate the effectiveness of the adapters on fourteen datasets from two different reasoning tasks Arithmetic Reasoning and Commonsense Reasoning. The results demonstrate that using adapter45;based PEFT in smaller45;scale LLMs (7B) with few extra trainable parameters yields comparable and in some cases superior performance to powerful LLMs (175B) in zero45;shot inference on both reasoning tasks.
