---
layout: publication
title: 'Webrl: Training LLM Web Agents Via Self-evolving Online Curriculum Reinforcement Learning'
authors: Zehan Qi, Xiao Liu, Iat Long Iong, Hanyu Lai, Xueqiao Sun, Wenyi Zhao, Yu Yang, Xinyue Yang, Jiadai Sun, Shuntian Yao, Tianjie Zhang, Wei Xu, Jie Tang, Yuxiao Dong
conference: "Arxiv"
year: 2024
bibkey: qi2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02337"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT']
---
Large language models (LLMs) have shown remarkable potential as autonomous
agents, particularly in web-based tasks. However, existing LLM web agents
heavily rely on expensive proprietary LLM APIs, while open LLMs lack the
necessary decision-making capabilities. This paper introduces WebRL, a
self-evolving online curriculum reinforcement learning framework designed to
train high-performance web agents using open LLMs. WebRL addresses three key
challenges in building LLM web agents, including the scarcity of training
tasks, sparse feedback signals, and policy distribution drift in online
learning. Specifically, WebRL incorporates 1) a self-evolving curriculum that
generates new tasks from unsuccessful attempts, 2) a robust outcome-supervised
reward model (ORM), and 3) adaptive reinforcement learning strategies to ensure
consistent improvements. We apply WebRL to transform open Llama-3.1 and GLM-4
models into proficient web agents. On WebArena-Lite, WebRL improves the success
rate of Llama-3.1-8B from 4.8% to 42.4%, and from 6.1% to 43% for GLM-4-9B.
These open models significantly surpass the performance of GPT-4-Turbo (17.6%)
and GPT-4o (13.9%) and outperform previous state-of-the-art web agents trained
on open LLMs (AutoWebGLM, 18.2%). Our findings demonstrate WebRL's
effectiveness in bridging the gap between open and proprietary LLM-based web
agents, paving the way for more accessible and powerful autonomous web
interaction systems.
