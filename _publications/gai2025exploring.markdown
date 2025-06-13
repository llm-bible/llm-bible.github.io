---
layout: publication
title: 'Exploring Code Language Models For Automated Hls-based Hardware Generation: Benchmark, Infrastructure And Analysis'
authors: Jiahao Gai, Hao Mark Chen, Zhican Wang, Hongyu Zhou, Wanru Zhao, Nicholas Lane, Hongxiang Fan
conference: "Arxiv"
year: 2025
bibkey: gai2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13921"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications']
---
Recent advances in code generation have illuminated the potential of
employing large language models (LLMs) for general-purpose programming
languages such as Python and C++, opening new opportunities for automating
software development and enhancing programmer productivity. The potential of
LLMs in software programming has sparked significant interest in exploring
automated hardware generation and automation. Although preliminary endeavors
have been made to adopt LLMs in generating hardware description languages
(HDLs), several challenges persist in this direction. First, the volume of
available HDL training data is substantially smaller compared to that for
software programming languages. Second, the pre-trained LLMs, mainly tailored
for software code, tend to produce HDL designs that are more error-prone.
Third, the generation of HDL requires a significantly higher number of tokens
compared to software programming, leading to inefficiencies in cost and energy
consumption. To tackle these challenges, this paper explores leveraging LLMs to
generate High-Level Synthesis (HLS)-based hardware design. Although code
generation for domain-specific programming languages is not new in the
literature, we aim to provide experimental results, insights, benchmarks, and
evaluation infrastructure to investigate the suitability of HLS over low-level
HDLs for LLM-assisted hardware design generation. To achieve this, we first
finetune pre-trained models for HLS-based hardware generation, using a
collected dataset with text prompts and corresponding reference HLS designs. An
LLM-assisted framework is then proposed to automate end-to-end hardware code
generation, which also investigates the impact of chain-of-thought and feedback
loops promoting techniques on HLS-design generation. Limited by the timeframe
of this research, we plan to evaluate more advanced reasoning models in the
future.
