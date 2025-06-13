---
layout: publication
title: 'RLTF: Reinforcement Learning From Unit Test Feedback'
authors: Jiate Liu, Yiqin Zhu, Kaiwen Xiao, Qiang Fu, Xiao Han, Wei Yang, Deheng Ye
conference: "Arxiv"
year: 2023
bibkey: liu2023reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.04349"}
  - {name: "Code", url: "https://github.com/Zyq-scut/RLTF"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Fine-Tuning', 'Has Code', 'Applications']
---
The goal of program synthesis, or code generation, is to generate executable
code based on given descriptions. Recently, there has been an increasing number
of studies employing reinforcement learning (RL) to improve the performance of
large language models (LLMs) for code. However, current representative works
either rely solely on offline frameworks, limiting the exploration of new
sample spaces, or fall short in the utilization of unit test signals, not
accounting for specific error locations within the code. To address these
issues, we propose RLTF, i.e., Reinforcement Learning from Unit Test Feedback,
a novel online RL framework with unit test feedback of multi-granularity for
refining code LLMs. Our approach generates data in real-time during training
and simultaneously utilizes fine-grained feedback signals to guide the model
towards producing higher-quality code. Extensive experiments show that RLTF
achieves state-of-the-art performance on the APPS and the MBPP benchmarks. Our
code is available at: https://github.com/Zyq-scut/RLTF.
