---
layout: publication
title: Self-driven Grounding Large Language Model Agents with Automatical Language-aligned Skill Learning
authors: Peng Shaohui, Hu Xing, Yi Qi, Zhang Rui, Guo Jiaming, Huang Di, Tian Zikang, Chen Ruizhi, Du Zidong, Guo Qi, Chen Yunji, Li Ling
conference: "Arxiv"
year: 2023
bibkey: peng2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.01352"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) show their powerful automatic reasoning and planning capability with a wealth of semantic knowledge about the human world. However the grounding problem still hinders the applications of LLMs in the real-world environment. Existing studies try to fine-tune the LLM or utilize pre-defined behavior APIs to bridge the LLMs and the environment which not only costs huge human efforts to customize for every single task but also weakens the generality strengths of LLMs. To autonomously ground the LLM onto the environment we proposed the Self-Driven Grounding (SDG) framework to automatically and progressively ground the LLM with self-driven skill learning. SDG first employs the LLM to propose the hypothesis of sub-goals to achieve tasks and then verify the feasibility of the hypothesis via interacting with the underlying environment. Once verified SDG can then learn generalized skills with the guidance of these successfully grounded subgoals. These skills can be further utilized to accomplish more complex tasks which fail to pass the verification phase. Verified in the famous instruction following task set-BabyAI SDG achieves comparable performance in the most challenging tasks compared with imitation learning methods that cost millions of demonstrations proving the effectiveness of learned skills and showing the feasibility and efficiency of our framework.
