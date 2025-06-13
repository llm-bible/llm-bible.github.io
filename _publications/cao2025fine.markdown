---
layout: publication
title: 'Safedialbench: A Fine-grained Safety Benchmark For Large Language Models In Multi-turn Dialogues With Diverse Jailbreak Attacks'
authors: Hongye Cao, Yanming Wang, Sijia Jing, Ziyue Peng, Zhixin Bai, Zhe Cao, Meng Fang, Fan Feng, Boyan Wang, Jiaheng Liu, Tianpei Yang, Jing Huo, Yang Gao, Fanyu Meng, Xi Yang, Chao Deng, Junlan Feng
conference: "Arxiv"
year: 2025
bibkey: cao2025fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11090"}
tags: ['Responsible AI', 'Security', 'Tools']
---
With the rapid advancement of Large Language Models (LLMs), the safety of
LLMs has been a critical concern requiring precise assessment. Current
benchmarks primarily concentrate on single-turn dialogues or a single jailbreak
attack method to assess the safety. Additionally, these benchmarks have not
taken into account the LLM's capability of identifying and handling unsafe
information in detail. To address these issues, we propose a fine-grained
benchmark SafeDialBench for evaluating the safety of LLMs across various
jailbreak attacks in multi-turn dialogues. Specifically, we design a two-tier
hierarchical safety taxonomy that considers 6 safety dimensions and generates
more than 4000 multi-turn dialogues in both Chinese and English under 22
dialogue scenarios. We employ 7 jailbreak attack strategies, such as reference
attack and purpose reverse, to enhance the dataset quality for dialogue
generation. Notably, we construct an innovative assessment framework of LLMs,
measuring capabilities in detecting, and handling unsafe information and
maintaining consistency when facing jailbreak attacks. Experimental results
across 17 LLMs reveal that Yi-34B-Chat and GLM4-9B-Chat demonstrate superior
safety performance, while Llama3.1-8B-Instruct and o3-mini exhibit safety
vulnerabilities.
