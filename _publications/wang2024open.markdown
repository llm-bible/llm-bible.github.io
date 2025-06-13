---
layout: publication
title: 'Openr: An Open Source Framework For Advanced Reasoning With Large Language Models'
authors: Jun Wang, Meng Fang, Ziyu Wan, Muning Wen, Jiachen Zhu, Anjie Liu, Ziqin Gong, Yan Song, Lei Chen, Lionel M. Ni, Linyi Yang, Ying Wen, Weinan Zhang
conference: "Arxiv"
year: 2024
bibkey: wang2024open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09671"}
  - {name: "Code", url: "https://openreasoner.github.io"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Has Code', 'Dataset']
---
In this technical report, we introduce OpenR, an open-source framework
designed to integrate key components for enhancing the reasoning capabilities
of large language models (LLMs). OpenR unifies data acquisition, reinforcement
learning training (both online and offline), and non-autoregressive decoding
into a cohesive software platform. Our goal is to establish an open-source
platform and community to accelerate the development of LLM reasoning. Inspired
by the success of OpenAI's o1 model, which demonstrated improved reasoning
abilities through step-by-step reasoning and reinforcement learning, OpenR
integrates test-time compute, reinforcement learning, and process supervision
to improve reasoning in LLMs. Our work is the first to provide an open-source
framework that explores the core techniques of OpenAI's o1 model with
reinforcement learning, achieving advanced reasoning capabilities beyond
traditional autoregressive methods. We demonstrate the efficacy of OpenR by
evaluating it on the MATH dataset, utilising publicly available data and search
methods. Our initial experiments confirm substantial gains, with relative
improvements in reasoning and performance driven by test-time computation and
reinforcement learning through process reward models. The OpenR framework,
including code, models, and datasets, is accessible at
https://openreasoner.github.io.
