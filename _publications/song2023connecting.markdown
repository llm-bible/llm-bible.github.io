---
layout: publication
title: 'Restgpt: Connecting Large Language Models With Real-world Restful Apis'
authors: Yifan Song, Weimin Xiong, Dawei Zhu, Wenhao Wu, Han Qian, Mingbo Song, Hailiang Huang, Cheng Li, Ke Wang, Rong Yao, Ye Tian, Sujian Li
conference: "Arxiv"
year: 2023
bibkey: song2023connecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.06624"}
  - {name: "Code", url: "https://restgpt.github.io/"}
tags: ['Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Has Code']
---
Tool-augmented large language models (LLMs) have achieved remarkable progress
in tackling a broad range of tasks. However, existing methods are mainly
restricted to specifically designed tools and fail to fulfill complex
instructions, having great limitations when confronted with real-world
scenarios. In this paper, we explore a more realistic scenario by connecting
LLMs with RESTful APIs, which adhere to the widely adopted REST software
architectural style for web service development. To address the practical
challenges of tackling complex instructions, we propose RestGPT, which exploits
the power of LLMs and conducts a coarse-to-fine online planning mechanism to
enhance the abilities of task decomposition and API selection. RestGPT also
contains an API executor tailored for calling RESTful APIs, which can
meticulously formulate parameters and parse API responses. To fully evaluate
the performance of RestGPT, we propose RestBench, a high-quality benchmark
which consists of two real-world scenarios and human-annotated instructions
with gold solution paths. Experiments show that RestGPT is able to achieve
impressive results in complex tasks and has strong robustness, which paves a
new way towards AGI. RestGPT and RestBench is publicly available at
https://restgpt.github.io/.
