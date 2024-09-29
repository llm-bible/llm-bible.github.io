---
layout: publication
title: DP45;OPT Make Large Language Model Your Privacy45;preserving Prompt Engineer
authors: Hong Junyuan, Wang Jiachen T., Zhang Chenhui, Li Zhangheng, Li Bo, Wang Zhangyang
conference: "Arxiv"
year: 2023
bibkey: hong2023dp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.03724"}
  - {name: "Code", url: "https://github.com/VITA&#45;Group/DP&#45;OPT"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'TACL', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have emerged as dominant tools for various tasks particularly when tailored for a specific target by prompt tuning. Nevertheless concerns surrounding data privacy present obstacles due to the tuned prompts dependency on sensitive private information. A practical solution is to host a local LLM and optimize a soft prompt privately using data. Yet hosting a local model becomes problematic when model ownership is protected. Alternative methods like sending data to the models provider for training intensify these privacy issues facing an untrusted provider. In this paper we present a novel solution called Differentially45;Private Offsite Prompt Tuning (DP45;OPT) to address this challenge. Our approach involves tuning a discrete prompt on the client side and then applying it to the desired cloud models. We demonstrate that prompts suggested by LLMs themselves can be transferred without compromising performance significantly. To ensure that the prompts do not leak private information we introduce the first private prompt generation mechanism by a differentially45;private (DP) ensemble of in45;context learning with private demonstrations. With DP45;OPT generating privacy45;preserving prompts by Vicuna45;7b can yield competitive performance compared to non45;private in45;context learning on GPT3.5 or local private prompt tuning. Codes are available at https://github.com/VITA&#45;Group/DP&#45;OPT .
