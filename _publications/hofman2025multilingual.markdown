---
layout: publication
title: 'MAPS: A Multilingual Benchmark For Global Agent Performance And Security'
authors: Omer Hofman, Oren Rachmil, Shamik Bose, Vikas Pahuja, Jonathan Brokman, Toshiya Shimizu, Trisha Starostina, Kelly Marchisio, Seraphina Goldfarb-tarrant, Roman Vainshtein
conference: "Arxiv"
year: 2025
bibkey: hofman2025multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15935"}
  - {name: "Code", url: "https://huggingface.co/datasets/Fujitsu-FRE/MAPS"}
tags: ['Responsible AI', 'Agentic', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Security', 'Has Code']
---
Agentic AI systems, which build on Large Language Models (LLMs) and interact with tools and memory, have rapidly advanced in capability and scope. Yet, since LLMs have been shown to struggle in multilingual settings, typically resulting in lower performance and reduced safety, agentic systems risk inheriting these limitations. This raises concerns about the global accessibility of such systems, as users interacting in languages other than English may encounter unreliable or security-critical agent behavior. Despite growing interest in evaluating agentic AI, existing benchmarks focus exclusively on English, leaving multilingual settings unexplored. To address this gap, we propose MAPS, a multilingual benchmark suite designed to evaluate agentic AI systems across diverse languages and tasks. MAPS builds on four widely used agentic benchmarks - GAIA (real-world tasks), SWE-bench (code generation), MATH (mathematical reasoning), and the Agent Security Benchmark (security). We translate each dataset into ten diverse languages, resulting in 805 unique tasks and 8,855 total language-specific instances. Our benchmark suite enables a systematic analysis of how multilingual contexts affect agent performance and robustness. Empirically, we observe consistent degradation in both performance and security when transitioning from English to other languages, with severity varying by task and correlating with the amount of translated input. Building on these findings, we provide actionable recommendations to guide agentic AI systems development and assessment under multilingual settings. This work establishes a standardized evaluation framework, encouraging future research towards equitable, reliable, and globally accessible agentic AI. MAPS benchmark suite is publicly available at https://huggingface.co/datasets/Fujitsu-FRE/MAPS
