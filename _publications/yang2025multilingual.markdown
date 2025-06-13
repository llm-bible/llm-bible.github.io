---
layout: publication
title: 'Macosworld: A Multilingual Interactive Benchmark For GUI Agents'
authors: Pei Yang, Hai Ci, Mike Zheng Shou
conference: "Arxiv"
year: 2025
bibkey: yang2025multilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.04135'}
  - {name: "Code", url: 'https://github.com/showlab/macosworld'}
tags: ['Attention Mechanism', 'Agentic', 'Has Code', 'RAG', 'Security', 'Model Architecture', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Responsible AI']
---
Graphical User Interface (GUI) agents show promising capabilities for automating computer-use tasks and facilitating accessibility, but existing interactive benchmarks are mostly English-only, covering web-use or Windows, Linux, and Android environments, but not macOS. macOS is a major OS with distinctive GUI patterns and exclusive applications. To bridge the gaps, we present macOSWorld, the first comprehensive benchmark for evaluating GUI agents on macOS. macOSWorld features 202 multilingual interactive tasks across 30 applications (28 macOS-exclusive), with task instructions and OS interfaces offered in 5 languages (English, Chinese, Arabic, Japanese, and Russian). As GUI agents are shown to be vulnerable to deception attacks, macOSWorld also includes a dedicated safety benchmarking subset. Our evaluation on six GUI agents reveals a dramatic gap: proprietary computer-use agents lead at above 30% success rate, while open-source lightweight research models lag at below 2%, highlighting the need for macOS domain adaptation. Multilingual benchmarks also expose common weaknesses, especially in Arabic, with a 27.5% average degradation compared to English. Results from safety benchmarking also highlight that deception attacks are more general and demand immediate attention. macOSWorld is available at https://github.com/showlab/macosworld.
