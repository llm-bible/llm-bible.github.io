---
layout: publication
title: An Extremely Data-efficient And Generative Llm-based Reinforcement Learning Agent For Recommenders
authors: Feng Shuang, Feng Grace
conference: "Arxiv"
year: 2024
bibkey: feng2024extremely
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16032"}
tags: ['Agent', 'Agentic', 'BERT', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Recent advancements in large language models (LLMs) have enabled understanding webpage contexts product details and human instructions. Utilizing LLMs as the foundational architecture for either reward models or policies in reinforcement learning has gained popularity -- a notable achievement is the success of InstructGPT. RL algorithms have been instrumental in maximizing long-term customer satisfaction and avoiding short-term myopic goals in industrial recommender systems which often rely on deep learning models to predict immediate clicks or purchases. In this project several RL methods are implemented and evaluated using the WebShop benchmark environment data simulator and pre-trained model checkpoints. The goal is to train an RL agent to maximize the purchase reward given a detailed human instruction describing a desired product. The RL agents are developed by fine-tuning a pre-trained BERT model with various objectives learning from preferences without a reward model and employing contemporary training techniques such as Proximal Policy Optimization (PPO) as used in InstructGPT and Direct Preference Optimization (DPO). This report also evaluates the RL agents trained using generative trajectories. Evaluations were conducted using Thompson sampling in the WebShop simulator environment. The simulated online experiments demonstrate that agents trained on generated trajectories exhibited comparable task performance to those trained using human trajectories. This has demonstrated an example of an extremely low-cost data-efficient way of training reinforcement learning agents. Also with limited training time (<2hours) without utilizing any images a DPO agent achieved a 1937; success rate after approximately 3000 steps or 30 minutes of training on T4 GPUs compared to a PPO agent which reached a 1537; success rate.
