---
layout: publication
title: 'Extracting Prompts By Inverting LLM Outputs'
authors: Zhang Collin, Morris John X., Shmatikov Vitaly
conference: "Arxiv"
year: 2024
bibkey: zhang2024extracting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15012"}
tags: ['Efficiency And Optimization', 'Prompting', 'Security', 'Uncategorized']
---
We consider the problem of language model inversion: given outputs of a language model, we seek to extract the prompt that generated these outputs. We develop a new black-box method, output2prompt, that learns to extract prompts without access to the model's logits and without adversarial or jailbreaking queries. In contrast to previous work, output2prompt only needs outputs of normal user queries. To improve memory efficiency, output2prompt employs a new sparse encoding techique. We measure the efficacy of output2prompt on a variety of user and system prompts and demonstrate zero-shot transferability across different LLMs.
