---
layout: publication
title: 'Atlas: Agent Tuning Via Learning Critical Steps'
authors: Zhixun Chen, Ming Li, Yuxuan Huang, Yali Du, Meng Fang, Tianyi Zhou
conference: "Arxiv"
year: 2025
bibkey: chen2025agent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02197"}
tags: ['Agentic', 'Ethics and Bias', 'Training Techniques']
---
Large Language Model (LLM) agents have demonstrated remarkable generalization capabilities across multi-domain tasks. Existing agent tuning approaches typically employ supervised finetuning on entire expert trajectories. However, behavior-cloning of full trajectories can introduce expert bias and weaken generalization to states not covered by the expert data. Additionally, critical steps, such as planning, complex reasoning for intermediate subtasks, and strategic decision-making, are essential to success in agent tasks, so learning these steps is the key to improving LLM agents. For more effective and efficient agent tuning, we propose ATLaS that identifies the critical steps in expert trajectories and finetunes LLMs solely on these steps with reduced costs. By steering the training's focus to a few critical steps, our method mitigates the risk of overfitting entire trajectories and promotes generalization across different environments and tasks. In extensive experiments, an LLM finetuned on only 30% critical steps selected by ATLaS outperforms the LLM finetuned on all steps and recent open-source LLM agents. ATLaS maintains and improves base LLM skills as generalist agents interacting with diverse environments.
