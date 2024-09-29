---
layout: publication
title: Nevermind Instruction Override And Moderation In Large Language Models
authors: Kim Edward
conference: "Arxiv"
year: 2024
bibkey: kim2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03303"}
tags: ['Pretraining Methods', 'Prompting', 'Responsible AI']
---
Given the impressive capabilities of recent Large Language Models (LLMs) we investigate and benchmark the most popular proprietary and different sized open source models on the task of explicit instruction following in conflicting situations e.g. overrides. These include the ability of the model to override the knowledge within the weights of the model the ability to override (or moderate) extracted knowledge in the prompt and lastly the ability to perform a full jailbreak. Experimentation performed suggest several key findings to improve instruction following 45; larger models perform the best in following instructions that override internal and contextual instructions and are obedient even to a fault. When scaling to longer contexts via rope scaling a significant buffer needs to be maintained from the edge of the perplexity cliff in order to maintain instruction following capabilities. Finally we observe improving instruction following and subsequently instruction overrides/jailbreaks is fundamentally at odds with the ability of a language model to follow given safety filters or guidelines. Thus we postulate the most effective approach for safe trustworthy AI should be dealt external to the LLM itself.
