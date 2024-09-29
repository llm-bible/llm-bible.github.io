---
layout: publication
title: React Meets Actre: When Language Agents Enjoy Training Data Autonomy
authors: Yang Zonghan, Li Peng, Yan Ming, Zhang Ji, Huang Fei, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: yang2024react
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14589"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Language agents have demonstrated autonomous decision-making abilities by reasoning with foundation models. Recently efforts have been made to train language agents for performance improvement with multi-step reasoning and action trajectories as the training data. However collecting such trajectories still requires considerable human effort by either artificial annotation or implementations of diverse prompting frameworks. In this work we propose A^3T a framework that enables the Autonomous Annotation of Agent Trajectories in the style of ReAct. The central role is an ActRe prompting agent which explains the reason for an arbitrary action. When randomly sampling an external action the ReAct-style agent could query the ActRe agent with the action to obtain its textual rationales. Novel trajectories are then synthesized by prepending the posterior reasoning from ActRe to the sampled action. In this way the ReAct-style agent executes multiple trajectories for the failed tasks and selects the successful ones to supplement its failed trajectory for contrastive self-training. Realized by policy gradient methods with binarized rewards the contrastive self-training with accumulated trajectories facilitates a closed loop for multiple rounds of language agent self-improvement. We conduct experiments using QLoRA fine-tuning with the open-sourced Mistral-7B-Instruct-v0.2. In AlfWorld the agent trained with A^3T obtains a 1-shot success rate of 9637; and 10037; success with 4 iterative rounds. In WebShop the 1-shot performance of the A^3T agent matches human average and 4 rounds of iterative refinement lead to the performance approaching human experts. A^3T agents significantly outperform existing techniques including prompting with GPT-4 advanced agent frameworks and fully fine-tuned LLMs.
