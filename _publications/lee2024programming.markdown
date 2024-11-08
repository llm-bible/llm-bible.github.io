---
layout: publication
title: 'Programming Refusal With Conditional Activation Steering'
authors: Lee Bruce W., Padhi Inkit, Ramamurthy Karthikeyan Natesan, Miehling Erik, Dognin Pierre, Nagireddy Manish, Dhurandhar Amit
conference: "Arxiv"
year: 2024
bibkey: lee2024programming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.05907"}
tags: ['Efficiency And Optimization', 'Prompting', 'Tools']
---
LLMs have shown remarkable capabilities, but precisely controlling their
response behavior remains challenging. Existing activation steering methods
alter LLM behavior indiscriminately, limiting their practical applicability in
settings where selective responses are essential, such as content moderation or
domain-specific assistants. In this paper, we propose Conditional Activation
Steering (CAST), which analyzes LLM activation patterns during inference to
selectively apply or withhold activation steering based on the input context.
Our method is based on the observation that different categories of prompts
activate distinct patterns in the model's hidden states. Using CAST, one can
systematically control LLM behavior with rules like "if input is about hate
speech or adult content, then refuse" or "if input is not about legal advice,
then refuse." This allows for selective modification of responses to specific
content while maintaining normal responses to other content, all without
requiring weight optimization. We release an open-source implementation of our
framework.
