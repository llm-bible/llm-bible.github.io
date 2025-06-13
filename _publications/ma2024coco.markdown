---
layout: publication
title: 'Coco-agent: A Comprehensive Cognitive MLLM Agent For Smartphone GUI Automation'
authors: Xinbei Ma, Zhuosheng Zhang, Hai Zhao
conference: "Arxiv"
year: 2024
bibkey: ma2024coco
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11941"}
  - {name: "Code", url: "https://github.com/xbmxb/CoCo-Agent"}
tags: ['Agentic', 'Multimodal Models', 'Has Code', 'Reinforcement Learning']
---
Multimodal large language models (MLLMs) have shown remarkable potential as
human-like autonomous language agents to interact with real-world environments,
especially for graphical user interface (GUI) automation. However, those GUI
agents require comprehensive cognition ability including exhaustive perception
and reliable action response. We propose a Comprehensive Cognitive LLM Agent,
CoCo-Agent, with two novel approaches, comprehensive environment perception
(CEP) and conditional action prediction (CAP), to systematically improve the
GUI automation performance. First, CEP facilitates the GUI perception through
different aspects and granularity, including screenshots and complementary
detailed layouts for the visual channel and historical actions for the textual
channel. Second, CAP decomposes the action prediction into sub-problems: action
type prediction and action target conditioned on the action type. With our
technical design, our agent achieves new state-of-the-art performance on AITW
and META-GUI benchmarks, showing promising abilities in realistic scenarios.
Code is available at https://github.com/xbmxb/CoCo-Agent.
