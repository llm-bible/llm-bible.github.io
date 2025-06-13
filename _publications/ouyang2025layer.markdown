---
layout: publication
title: 'Layer-level Self-exposure And Patch: Affirmative Token Mitigation For Jailbreak Attack Defense'
authors: Yang Ouyang, Hengrui Gu, Shuhang Lin, Wenyue Hua, Jie Peng, Bhavya Kailkhura, Meijun Gao, Tianlong Chen, Kaixiong Zhou
conference: "Arxiv"
year: 2025
bibkey: ouyang2025layer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02629"}
  - {name: "Code", url: "https://github.com/oyy2000/LayerAdvPatcher"}
tags: ['Responsible AI', 'Security', 'Tools', 'Has Code', 'Prompting', 'Applications']
---
As large language models (LLMs) are increasingly deployed in diverse
applications, including chatbot assistants and code generation, aligning their
behavior with safety and ethical standards has become paramount. However,
jailbreak attacks, which exploit vulnerabilities to elicit unintended or
harmful outputs, threaten LLMs' safety significantly. In this paper, we
introduce Layer-AdvPatcher, a novel methodology designed to defend against
jailbreak attacks by utilizing an unlearning strategy to patch specific layers
within LLMs through self-augmented datasets. Our insight is that certain
layer(s), tend to produce affirmative tokens when faced with harmful prompts.
By identifying these layers and adversarially exposing them to generate more
harmful data, one can understand their inherent and diverse vulnerabilities to
attacks. With these exposures, we then "unlearn" these issues, reducing the
impact of affirmative tokens and hence minimizing jailbreak risks while keeping
the model's responses to safe queries intact. We conduct extensive experiments
on two models, four benchmark datasets, and multiple state-of-the-art jailbreak
attacks to demonstrate the efficacy of our approach. Results indicate that our
framework reduces the harmfulness and attack success rate of jailbreak attacks
without compromising utility for benign queries compared to recent defense
methods. Our code is publicly available at:
https://github.com/oyy2000/LayerAdvPatcher
