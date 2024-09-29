---
layout: publication
title: UPRISE Universal Prompt Retrieval For Improving Zero45;shot Evaluation
authors: Cheng Daixuan, Huang Shaohan, Bi Junyu, Zhan Yuefeng, Liu Jianfeng, Wang Yujing, Sun Hao, Wei Furu, Deng Denvy, Zhang Qi
conference: "Arxiv"
year: 2023
bibkey: cheng2023universal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.08518"}
  - {name: "Code", url: "https://github.com/microsoft/LMOps"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting']
---
Large Language Models (LLMs) are popular for their impressive abilities but the need for model45;specific fine45;tuning or task45;specific prompt engineering can hinder their generalization. We propose UPRISE (Universal Prompt Retrieval for Improving zero45;Shot Evaluation) which tunes a lightweight and versatile retriever that automatically retrieves prompts for a given zero45;shot task input. Specifically we demonstrate universality in a cross45;task and cross45;model scenario the retriever is tuned on a diverse set of tasks but tested on unseen task types; we use a small frozen LLM GPT45;Neo45;2.7B for tuning the retriever but test the retriever on different LLMs of much larger scales such as BLOOM45;7.1B OPT45;66B and GPT345;175B. Additionally we show that UPRISE mitigates the hallucination problem in our experiments with ChatGPT suggesting its potential to improve even the strongest LLMs. Our model and code are available at https://github.com/microsoft/LMOps.
