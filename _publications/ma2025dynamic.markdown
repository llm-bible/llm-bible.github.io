---
layout: publication
title: 'Dynamic Scaling Of Unit Tests For Code Reward Modeling'
authors: Zeyao Ma, Xiaokang Zhang, Jing Zhang, Jifan Yu, Sijia Luo, Jie Tang
conference: "Arxiv"
year: 2025
bibkey: ma2025dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01054"}
tags: ['Efficiency and Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Current large language models (LLMs) often struggle to produce accurate
responses on the first attempt for complex reasoning tasks like code
generation. Prior research tackles this challenge by generating multiple
candidate solutions and validating them with LLM-generated unit tests. The
execution results of unit tests serve as reward signals to identify correct
solutions. As LLMs always confidently make mistakes, these unit tests are not
reliable, thereby diminishing the quality of reward signals. Motivated by the
observation that scaling the number of solutions improves LLM performance, we
explore the impact of scaling unit tests to enhance reward signal quality. Our
pioneer experiment reveals a positive correlation between the number of unit
tests and reward signal quality, with greater benefits observed in more
challenging problems. Based on these insights, we propose CodeRM-8B, a
lightweight yet effective unit test generator that enables efficient and
high-quality unit test scaling. Additionally, we implement a dynamic scaling
mechanism that adapts the number of unit tests based on problem difficulty,
further improving efficiency. Experimental results show that our approach
significantly improves performance across various models on three benchmarks
(e.g., with gains of 18.43% for Llama3-8B and 3.42% for GPT-4o-mini on
HumanEval Plus).
