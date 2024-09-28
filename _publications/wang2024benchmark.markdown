---
layout: publication
title: Benchmark Self-Evolving A Multi-Agent Framework for Dynamic LLM Evaluation
authors: Wang Siyuan, Long Zhuohan, Fan Zhihao, Wei Zhongyu, Huang Xuanjing
conference: "Arxiv"
year: 2024
bibkey: wang2024benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11443"}
  - {name: "Code", url: "https://github.com/NanshineLoong/Self-Evolving-Benchmark)"}
tags: ['ARXIV', 'Agent', 'Has Code', 'LLM', 'Pretraining Methods', 'Tools']
---
This paper presents a benchmark self-evolving framework to dynamically evaluate rapidly advancing Large Language Models (LLMs) aiming for a more accurate assessment of their capabilities and limitations. We utilize a multi-agent system to manipulate the context or question of original instances reframing new evolving instances with high confidence that dynamically extend existing benchmarks. Towards a more scalable robust and fine-grained evaluation we implement six reframing operations to construct evolving instances testing LLMs against diverse queries data noise and probing their problem-solving sub-abilities. With this framework we extend benchmark datasets of four tasks. Experimental results show a general performance decline in most LLMs against their original results. This decline under our scalable and robust evaluations alongside our fine-grained evaluation more accurately reflect models capabilities. Besides our framework widens performance discrepancies both between different models and within the same model across various tasks facilitating more informed model selection for specific tasks (Code and data are available at https://github.com/NanshineLoong/Self-Evolving-Benchmark).
