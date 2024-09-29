---
layout: publication
title: Guiding Pretraining in Reinforcement Learning with Large Language Models
authors: Du Yuqing, Watkins Olivia, Wang Zihan, Colas Cédric, Darrell Trevor, Abbeel Pieter, Gupta Abhishek, Andreas Jacob
conference: "Arxiv"
year: 2023
bibkey: du2023guiding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.06692"}
  - {name: "Code", url: "https://github.com/yuqingd/ellm"}
tags: ['Agentic', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Reinforcement learning algorithms typically struggle in the absence of a dense well-shaped reward function. Intrinsically motivated exploration methods address this limitation by rewarding agents for visiting novel states or transitions but these methods offer limited benefits in large environments where most discovered novelty is irrelevant for downstream tasks. We describe a method that uses background knowledge from text corpora to shape exploration. This method called ELLM (Exploring with LLMs) rewards an agent for achieving goals suggested by a language model prompted with a description of the agents current state. By leveraging large-scale language model pretraining ELLM guides agents toward human-meaningful and plausibly useful behaviors without requiring a human in the loop. We evaluate ELLM in the Crafter game environment and the Housekeep robotic simulator showing that ELLM-trained agents have better coverage of common-sense behaviors during pretraining and usually match or improve performance on a range of downstream tasks. Code available at https://github.com/yuqingd/ellm.
