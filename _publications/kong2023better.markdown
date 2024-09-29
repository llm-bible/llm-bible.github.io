---
layout: publication
title: "Better Zero-shot Reasoning With Role-play Prompting"
authors: Kong Aobo, Zhao Shiwan, Chen Hao, Li Qicheng, Qin Yong, Sun Ruiqi, Zhou Xin, Wang Enzhi, Dong Xiaohang
conference: "Arxiv"
year: 2023
bibkey: kong2023better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.07702"}
  - {name: "Code", url: "https://github.com/NKU-HLT/Role-Play-Prompting"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
Modern large language models (LLMs) exhibit a remarkable capacity for role-playing enabling them to embody not only human characters but also non-human entities. This versatility allows them to simulate complex human-like interactions and behaviors within various contexts as well as to emulate specific objects or systems. While these capabilities have enhanced user engagement and introduced novel modes of interaction the influence of role-playing on LLMs reasoning abilities remains underexplored. In this study we introduce a strategically designed role-play prompting methodology and assess its performance under the zero-shot setting across twelve diverse reasoning benchmarks. Our empirical results illustrate that role-play prompting consistently surpasses the standard zero-shot approach across most datasets. Notably in experiments conducted using ChatGPT accuracy on AQuA rises from 53.537; to 63.837; and on Last Letter from 23.837; to 84.237;.Upon further comparison with the Zero-Shot-CoT technique which prompts the model to think step by step our study demonstrates that role-play prompting acts as a more effective trigger for the CoT process. This highlights its potential to augment the reasoning capabilities of LLMs. We release our code at https://github.com/NKU-HLT/Role-Play-Prompting."
