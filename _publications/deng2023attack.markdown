---
layout: publication
title: 'Attack Prompt Generation For Red Teaming And Defending Large Language Models'
authors: Boyi Deng, Wenjie Wang, Fuli Feng, Yang Deng, Qifan Wang, Xiangnan He
conference: "Arxiv"
year: 2023
bibkey: deng2023attack
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.12505'}
  - {name: "Code", url: 'https://github.com/Aatrox103/SAP'}
tags: ['Has Code', 'Security', 'Tools', 'Prompting', 'Responsible AI']
---
Large language models (LLMs) are susceptible to red teaming attacks, which
can induce LLMs to generate harmful content. Previous research constructs
attack prompts via manual or automatic methods, which have their own
limitations on construction cost and quality. To address these issues, we
propose an integrated approach that combines manual and automatic methods to
economically generate high-quality attack prompts. Specifically, considering
the impressive capabilities of newly emerged LLMs, we propose an attack
framework to instruct LLMs to mimic human-generated prompts through in-context
learning. Furthermore, we propose a defense framework that fine-tunes victim
LLMs through iterative interactions with the attack framework to enhance their
safety against red teaming attacks. Extensive experiments on different LLMs
validate the effectiveness of our proposed attack and defense frameworks.
Additionally, we release a series of attack prompts datasets named SAP with
varying sizes, facilitating the safety evaluation and enhancement of more LLMs.
Our code and dataset is available on https://github.com/Aatrox103/SAP .
