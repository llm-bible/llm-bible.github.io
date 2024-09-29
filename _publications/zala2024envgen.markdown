---
layout: publication
title: EnvGen Generating and Adapting Environments via LLMs for Training Embodied Agents
authors: Zala Abhay, Cho Jaemin, Lin Han, Yoon Jaehong, Bansal Mohit
conference: "Arxiv"
year: 2024
bibkey: zala2024envgen
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12014"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent SOTA approaches for embodied learning via interaction directly employ large language models (LLMs) as agents to determine the next steps in an environment. Due to their world knowledge and reasoning capabilities LLM agents achieve stronger performance than previous smaller agents based on reinforcement learning (RL); however frequently calling LLMs is slow and expensive. Instead of directly employing LLMs as agents can we use LLMs reasoning capabilities to adaptively create training environments to help smaller RL agents learn useful skills that they are weak at We propose EnvGen a novel framework to address this question. We first prompt an LLM to generate training environments by giving it the task description and simulator objectives that the agents should learn and then asking it to generate a set of environment configurations (e.g. different terrains items initially given to agents etc.). Next we train a small RL agent in a mixture of the original and LLM-generated environments. Then we enable the LLM to continuously adapt the generated environments to progressively improve the skills that the agent is weak at by providing feedback to the LLM in the form of the agents performance. We demonstrate the usefulness of EnvGen with comprehensive experiments in Crafter and Heist environments. We find that a small RL agent trained with EnvGen can outperform SOTA methods including a GPT-4 agent and learns long-horizon tasks significantly faster. We also show that using an LLM to adapt environments dynamically outperforms curriculum learning approaches and how the environments are adapted to help improve RL agents weaker skills over time. Additionally EnvGen is substantially more efficient as it only uses a small number of LLM calls (e.g. 4 in total) whereas LLM agents require thousands of calls. Lastly we present detailed ablation studies for EnvGen design choices.
