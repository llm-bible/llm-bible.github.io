---
layout: publication
title: 'Federated Fine-tuning Of Llms On The Very Edge: The Good, The Bad, The Ugly'
authors: Herbert Woisetschläger, Alexander Isenko, Shiqiang Wang, Ruben Mayer, Hans-arno Jacobsen
conference: "Arxiv"
year: 2023
bibkey: woisetschläger2023federated
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.03150'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLM) and foundation models are popular as they offer
new opportunities for individuals and businesses to improve natural language
processing, interact with data, and retrieve information faster. However,
training or fine-tuning LLMs requires a vast amount of data, which can be
challenging to access due to legal or technical restrictions and may require
private computing resources. Federated Learning (FL) is a solution designed to
overcome these challenges and expand data access for deep learning
applications.
  This paper takes a hardware-centric approach to explore how LLMs can be
brought to modern edge computing systems. Our study fine-tunes the FLAN-T5
model family, ranging from 80M to 3B parameters, using FL for a text
summarization task. We provide a micro-level hardware benchmark, compare the
model FLOP utilization to a state-of-the-art data center GPU, and study the
network utilization in realistic conditions. Our contribution is twofold:
First, we evaluate the current capabilities of edge computing systems and their
potential for LLM FL workloads. Second, by comparing these systems with a
data-center GPU, we demonstrate the potential for improvement and the next
steps toward achieving greater computational efficiency at the edge.
