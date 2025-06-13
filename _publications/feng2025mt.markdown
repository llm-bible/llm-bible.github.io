---
layout: publication
title: 'Mt-r1-zero: Advancing Llm-based Machine Translation Via R1-zero-like Reinforcement Learning'
authors: Zhaopeng Feng, Shaosheng Cao, Jiahan Ren, Jiayuan Su, Ruizhe Chen, Yan Zhang, Zhe Xu, Yao Hu, Jian Wu, Zuozhu Liu
conference: "Arxiv"
year: 2025
bibkey: feng2025mt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10160"}
  - {name: "Code", url: "https://github.com/fzp0424/MT-R1-Zero"}
tags: ['Agentic', 'WMT', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
Large-scale reinforcement learning (RL) methods have proven highly effective
in enhancing the reasoning abilities of large language models (LLMs),
particularly for tasks with verifiable solutions such as mathematics and
coding. However, applying this idea to machine translation (MT), where outputs
are flexibly formatted and difficult to automatically evaluate with explicit
rules, remains underexplored. In this work, we introduce MT-R1-Zero, the first
open-source adaptation of the R1-Zero RL framework for MT without supervised
fine-tuning or cold-start. We propose a rule-metric mixed reward mechanism to
guide LLMs towards improved translation quality via emergent reasoning. On the
WMT 24 English-Chinese benchmark, our MT-R1-Zero-3B-Mix achieves competitive
performance, surpassing TowerInstruct-7B-v0.2 by an average of 1.26 points.
Meanwhile, our MT-R1-Zero-7B-Mix attains a high average score of 62.25 across
all metrics, placing it on par with advanced proprietary models such as GPT-4o
and Claude-3.5-Sonnet, while the MT-R1-Zero-7B-Sem variant achieves
state-of-the-art scores on semantic metrics. Moreover, our work exhibits strong
generalization capabilities on out-of-distribution MT tasks, robustly
supporting multilingual and low-resource settings. Extensive analysis of model
behavior across different initializations and reward metrics offers pioneering
insight into the critical role of reward design, LLM adaptability, training
dynamics, and emergent reasoning patterns within the R1-Zero paradigm for MT.
Our code is available at https://github.com/fzp0424/MT-R1-Zero.
