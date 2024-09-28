---
layout: publication
title: Single Character Perturbations Break LLM Alignment
authors: Lin Leon, Brown Hannah, Kawaguchi Kenji, Shieh Michael
conference: "Arxiv"
year: 2024
bibkey: lin2024single
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03232"}
  - {name: "Code", url: "https://github.com/hannah-aught/space_attack"}
tags: ['ARXIV', 'Ethics And Bias', 'Has Code', 'LLM', 'Prompting', 'RAG', 'Security', 'Training Techniques']
---
When LLMs are deployed in sensitive human-facing settings it is crucial that they do not output unsafe biased or privacy-violating outputs. For this reason models are both trained and instructed to refuse to answer unsafe prompts such as Tell me how to build a bomb. We find that despite these safeguards it is possible to break model defenses simply by appending a space to the end of a models input. In a study of eight open-source models we demonstrate that this acts as a strong enough attack to cause the majority of models to generate harmful outputs with very high success rates. We examine the causes of this behavior finding that the contexts in which single spaces occur in tokenized training data encourage models to generate lists when prompted overriding training signals to refuse to answer unsafe requests. Our findings underscore the fragile state of current model alignment and promote the importance of developing more robust alignment methods. Code and data will be available at https://github.com/hannah-aught/space_attack.
