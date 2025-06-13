---
layout: publication
title: 'Helpsteer3-preference: Open Human-annotated Preference Data Across Diverse Tasks And Languages'
authors: Zhilin Wang, Jiaqi Zeng, Olivier Delalleau, Hoo-chang Shin, Felipe Soares, Alexander Bukharin, Ellie Evans, Yi Dong, Oleksii Kuchaiev
conference: "Arxiv"
year: 2025
bibkey: wang2025open
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.11475'}
  - {name: "Code", url: 'https://huggingface.co/datasets/nvidia/HelpSteer3#preference'}
tags: ['Agentic', 'Has Code', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
Preference datasets are essential for training general-domain, instruction-following language models with Reinforcement Learning from Human Feedback (RLHF). Each subsequent data release raises expectations for future data collection, meaning there is a constant need to advance the quality and diversity of openly available preference data. To address this need, we introduce HelpSteer3-Preference, a permissively licensed (CC-BY-4.0), high-quality, human-annotated preference dataset comprising of over 40,000 samples. These samples span diverse real-world applications of large language models (LLMs), including tasks relating to STEM, coding and multilingual scenarios. Using HelpSteer3-Preference, we train Reward Models (RMs) that achieve top performance on RM-Bench (82.4%) and JudgeBench (73.7%). This represents a substantial improvement (~10% absolute) over the previously best-reported results from existing RMs. We demonstrate HelpSteer3-Preference can also be applied to train Generative RMs and how policy models can be aligned with RLHF using our RMs. Dataset (CC-BY-4.0): https://huggingface.co/datasets/nvidia/HelpSteer3%23preference
