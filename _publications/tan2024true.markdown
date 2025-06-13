---
layout: publication
title: 'True Knowledge Comes From Practice: Aligning Llms With Embodied Environments Via Reinforcement Learning'
authors: Weihao Tan, Wentao Zhang, Shanqi Liu, Longtao Zheng, Xinrun Wang, Bo An
conference: "Arxiv"
year: 2024
bibkey: tan2024true
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.14151"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Fine-Tuning', 'Prompting']
---
Despite the impressive performance across numerous tasks, large language
models (LLMs) often fail in solving simple decision-making tasks due to the
misalignment of the knowledge in LLMs with environments. On the contrary,
reinforcement learning (RL) agents learn policies from scratch, which makes
them always align with environments but difficult to incorporate prior
knowledge for efficient explorations. To narrow the gap, we propose TWOSOME, a
novel general online framework that deploys LLMs as decision-making agents to
efficiently interact and align with embodied environments via RL without
requiring any prepared datasets or prior knowledge of the environments.
Firstly, we query the joint probabilities of each valid action with LLMs to
form behavior policies. Then, to enhance the stability and robustness of the
policies, we propose two normalization methods and summarize four prompt design
principles. Finally, we design a novel parameter-efficient training
architecture where the actor and critic share one frozen LLM equipped with
low-rank adapters (LoRA) updated by PPO. We conduct extensive experiments to
evaluate TWOSOME. i) TWOSOME exhibits significantly better sample efficiency
and performance compared to the conventional RL method, PPO, and prompt tuning
method, SayCan, in both classical decision-making environment, Overcooked, and
simulated household environment, VirtualHome. ii) Benefiting from LLMs'
open-vocabulary feature, TWOSOME shows superior generalization ability to
unseen tasks. iii) Under our framework, there is no significant loss of the
LLMs' original ability during online PPO finetuning.
