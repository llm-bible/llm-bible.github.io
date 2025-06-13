---
layout: publication
title: 'DROJ: A Prompt-driven Attack Against Large Language Models'
authors: Leyang Hu, Boran Wang
conference: "Arxiv"
year: 2024
bibkey: hu2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.09125"}
  - {name: "Code", url: "https://github.com/Leon-Leyang/LLM-Safeguard"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) have demonstrated exceptional capabilities
across various natural language processing tasks. Due to their training on
internet-sourced datasets, LLMs can sometimes generate objectionable content,
necessitating extensive alignment with human feedback to avoid such outputs.
Despite massive alignment efforts, LLMs remain susceptible to adversarial
jailbreak attacks, which usually are manipulated prompts designed to circumvent
safety mechanisms and elicit harmful responses. Here, we introduce a novel
approach, Directed Rrepresentation Optimization Jailbreak (DROJ), which
optimizes jailbreak prompts at the embedding level to shift the hidden
representations of harmful queries towards directions that are more likely to
elicit affirmative responses from the model. Our evaluations on LLaMA-2-7b-chat
model show that DROJ achieves a 100% keyword-based Attack Success Rate (ASR),
effectively preventing direct refusals. However, the model occasionally
produces repetitive and non-informative responses. To mitigate this, we
introduce a helpfulness system prompt that enhances the utility of the model's
responses. Our code is available at
https://github.com/Leon-Leyang/LLM-Safeguard.
