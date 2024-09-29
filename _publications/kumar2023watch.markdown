---
layout: publication
title: Watch Your Language Investigating Content Moderation with Large Language Models
authors: Kumar Deepak, Abuhashem Yousef, Durumeric Zakir
conference: "Arxiv"
year: 2023
bibkey: kumar2023watch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.14517"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) have exploded in popularity due to their ability to perform a wide array of natural language tasks. Text-based content moderation is one LLM use case that has received recent enthusiasm however there is little research investigating how LLMs perform in content moderation settings. In this work we evaluate a suite of commodity LLMs on two common content moderation tasks rule-based community moderation and toxic content detection. For rule-based community moderation we instantiate 95 subcommunity specific LLMs by prompting GPT-3.5 with rules from 95 Reddit subcommunities. We find that GPT-3.5 is effective at rule-based moderation for many communities achieving a median accuracy of 64 and a median precision of 83. For toxicity detection we evaluate a suite of commodity LLMs (GPT-3 GPT-3.5 GPT-4 Gemini Pro LLAMA 2) and show that LLMs significantly outperform currently widespread toxicity classifiers. However recent increases in model size add only marginal benefit to toxicity detection suggesting a potential performance plateau for LLMs on toxicity detection tasks. We conclude by outlining avenues for future work in studying LLMs and content moderation.
