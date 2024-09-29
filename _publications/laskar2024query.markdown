---
layout: publication
title: Query45;opt Optimizing Inference Of Large Language Models Via Multi45;query Instructions In Meeting Summarization
authors: Laskar Md Tahmid Rahman, Khasanova Elena, Fu Xue-yong, Chen Cheng, Tn Shashi Bhushan
conference: "Arxiv"
year: 2024
bibkey: laskar2024query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.00067"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
This work focuses on the task of query45;based meeting summarization in which the summary of a context (meeting transcript) is generated in response to a specific query. When using Large Language Models (LLMs) for this task usually a new call to the LLM inference endpoint/API is triggered for each new query even if the context stays the same. However repeated calls to the LLM inference endpoints would significantly increase the costs of using them in production making LLMs impractical for many real45;world use cases. To address this problem in this paper we investigate whether combining the queries for the same input context in a single prompt to minimize repeated calls can be successfully used in meeting summarization. In this regard we conduct extensive experiments by comparing the performance of various popular LLMs GPT45;4 Gemini Claude45;3 LLaMA45;2 Mistral Phi45;3 and Qwen45;2 in single45;query and multi45;query settings. We observe that 10037; reliability in generating the response in the expected format is usually limited to certain closed45;source LLMs with most open45;source LLMs lagging behind (except a few 7B parameters LLMs like Mistral and Phi45;3). We conclude that multi45;query prompting could be useful to significantly optimize the inference costs in meeting summarization.
