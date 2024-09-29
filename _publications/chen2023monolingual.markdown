---
layout: publication
title: Monolingual Or Multilingual Instruction Tuning: Which Makes A Better Alpaca
authors: Chen Pinzhen, Ji Shaoxiong, Bogoychev Nikolay, Kutuzov Andrey, Haddow Barry, Heafield Kenneth
conference: "Arxiv"
year: 2023
bibkey: chen2023monolingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08958"}
tags: ['Applications', 'Reinforcement Learning', 'Training Techniques']
---
Foundational large language models (LLMs) can be instruction-tuned to perform open-domain question answering facilitating applications like chat assistants. While such efforts are often carried out in a single language we empirically analyze cost-efficient strategies for multilingual scenarios. Our study employs the Alpaca dataset and machine translations of it to form multilingual data which is then used to tune LLMs through either low-rank adaptation or full-parameter training. Under a controlled computation budget comparisons show that multilingual tuning is on par or better than tuning a model for each language. Furthermore multilingual tuning with downsampled data can be as powerful and more robust. Our findings serve as a guide for expanding language support through instruction tuning.
