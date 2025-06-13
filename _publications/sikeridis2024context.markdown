---
layout: publication
title: 'Pickllm: Context-aware Rl-assisted Large Language Model Routing'
authors: Dimitrios Sikeridis, Dennis Ramdass, Pranay Pareek
conference: "Arxiv"
year: 2024
bibkey: sikeridis2024context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12170"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Ethics and Bias', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Recently, the number of off-the-shelf Large Language Models (LLMs) has
exploded with many open-source options. This creates a diverse landscape
regarding both serving options (e.g., inference on local hardware vs remote LLM
APIs) and model heterogeneous expertise. However, it is hard for the user to
efficiently optimize considering operational cost (pricing structures,
expensive LLMs-as-a-service for large querying volumes), efficiency, or even
per-case specific measures such as response accuracy, bias, or toxicity. Also,
existing LLM routing solutions focus mainly on cost reduction, with response
accuracy optimizations relying on non-generalizable supervised training, and
ensemble approaches necessitating output computation for every considered LLM
candidate. In this work, we tackle the challenge of selecting the optimal LLM
from a model pool for specific queries with customizable objectives. We propose
PickLLM, a lightweight framework that relies on Reinforcement Learning (RL) to
route on-the-fly queries to available models. We introduce a weighted reward
function that considers per-query cost, inference latency, and model response
accuracy by a customizable scoring function. Regarding the learning algorithms,
we explore two alternatives: PickLLM router acting as a learning automaton that
utilizes gradient ascent to select a specific LLM, or utilizing stateless
Q-learning to explore the set of LLMs and perform selection with a
\\(\epsilon\\)-greedy approach. The algorithm converges to a single LLM for the
remaining session queries. To evaluate, we utilize a pool of four LLMs and
benchmark prompt-response datasets with different contexts. A separate scoring
function is assessing response accuracy during the experiment. We demonstrate
the speed of convergence for different learning rates and improvement in hard
metrics such as cost per querying session and overall response latency.
