---
layout: publication
title: Bita Bi45;directional Tuning For Lossless Acceleration In Large Language Models
authors: Lin Feng, Yi Hanling, Li Hongbin, Yang Yifan, Yu Xiaotian, Lu Guangming, Xiao Rong
conference: "Arxiv"
year: 2024
bibkey: lin2024bi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.12522"}
tags: ['Efficiency And Optimization', 'GPT', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) commonly employ autoregressive generation during inference leading to high memory bandwidth demand and consequently extended latency. To mitigate this inefficiency we present Bi45;directional Tuning for lossless Acceleration (BiTA) an innovative method expediting LLMs via streamlined semi45;autoregressive generation and draft verification. Inspired by the concept of prompt tuning we enhance LLMs with a parameter45;efficient design called bi45;directional tuning for the capability in semi45;autoregressive generation. Employing efficient tree45;based decoding the models perform draft candidate generation and verification in parallel ensuring outputs identical to their autoregressive counterparts under greedy sampling. BiTA serves as a lightweight plug45;in module seamlessly boosting the inference efficiency of existing LLMs without requiring additional assistance models or incurring significant extra memory costs. Applying the proposed BiTA LLaMA45;245;70B45;Chat achieves a 2.7× speedup on the MT45;Bench benchmark. Extensive experiments confirm our method surpasses state45;of45;the45;art acceleration techniques.
