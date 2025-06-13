---
layout: publication
title: 'Webevolver: Enhancing Web Agent Self-improvement With Coevolving World Model'
authors: Tianqing Fang, Hongming Zhang, Zhisong Zhang, Kaixin Ma, Wenhao Yu, Haitao Mi, Dong Yu
conference: "Arxiv"
year: 2025
bibkey: fang2025enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.21024'}
tags: ['Agentic', 'Agent', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning']
---
Agent self-improvement, where the backbone Large Language Model (LLM) of the
agent are trained on trajectories sampled autonomously based on their own
policies, has emerged as a promising approach for enhancing performance. Recent
advancements, particularly in web environments, face a critical limitation:
their performance will reach a stagnation point during autonomous learning
cycles, hindering further improvement. We argue that this stems from limited
exploration of the web environment and insufficient exploitation of pre-trained
web knowledge in LLMs. To improve the performance of self-improvement, we
propose a novel framework that introduces a co-evolving World Model LLM. This
world model predicts the next observation based on the current observation and
action within the web environment. Leveraging LLMs' pretrained knowledge of
abundant web content, the World Model serves dual roles: (1) as a virtual web
server generating self-instructed training data to continuously refine the
agent's policy, and (2) as an imagination engine during inference, enabling
look-ahead simulation to guide action selection for the agent LLM. Experiments
in real-world web environments (Mind2Web-Live, WebVoyager, and GAIA-web) show a
10% performance gain over existing self-evolving agents, demonstrating the
efficacy and generalizability of our approach, without using any distillation
from more powerful close-sourced models. Our work establishes the necessity of
integrating world models into autonomous agent frameworks to unlock sustained
adaptability.
