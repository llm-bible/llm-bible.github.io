---
layout: publication
title: 'Opencodereasoning: Advancing Data Distillation For Competitive Coding'
authors: Wasi Uddin Ahmad, Sean Narenthiran, Somshubra Majumdar, Aleksander Ficek, Siddhartha Jain, Jocelyn Huang, Vahid Noroozi, Boris Ginsburg
conference: "Arxiv"
year: 2025
bibkey: ahmad2025advancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01943'}
tags: ['Agentic', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Since the advent of reasoning-based large language models, many have found
great success from distilling reasoning capabilities into student models. Such
techniques have significantly bridged the gap between reasoning and standard
LLMs on coding tasks. Despite this, much of the progress on distilling
reasoning models remains locked behind proprietary datasets or lacks details on
data curation, filtering and subsequent training. To address this, we construct
a superior supervised fine-tuning (SFT) dataset that we use to achieve
state-of-the-art coding capability results in models of various sizes. Our
distilled models use only SFT to achieve 61.8% on LiveCodeBench and 24.6% on
CodeContests, surpassing alternatives trained with reinforcement learning. We
then perform analysis on the data sources used to construct our dataset, the
impact of code execution filtering, and the importance of instruction/solution
diversity. We observe that execution filtering negatively affected benchmark
accuracy, leading us to prioritize instruction diversity over solution
correctness. Finally, we also analyze the token efficiency and reasoning
patterns utilized by these models. We will open-source these datasets and
distilled models to the community.
