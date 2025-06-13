---
layout: publication
title: 'The Lighthouse Of Language: Enhancing LLM Agents Via Critique-guided Improvement'
authors: Ruihan Yang, Fanghua Ye, Jian Li, Siyu Yuan, Yikai Zhang, Zhaopeng Tu, Xiaolong Li, Deqing Yang
conference: "Arxiv"
year: 2025
bibkey: yang2025lighthouse
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.16024'}
tags: ['Agentic', 'Agent', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Reinforcement Learning']
---
Large language models (LLMs) have recently transformed from text-based
assistants to autonomous agents capable of planning, reasoning, and iteratively
improving their actions. While numerical reward signals and verifiers can
effectively rank candidate actions, they often provide limited contextual
guidance. In contrast, natural language feedback better aligns with the
generative capabilities of LLMs, providing richer and more actionable
suggestions. However, parsing and implementing this feedback effectively can be
challenging for LLM-based agents. In this work, we introduce Critique-Guided
Improvement (CGI), a novel two-player framework, comprising an actor model that
explores an environment and a critic model that generates detailed nature
language feedback. By training the critic to produce fine-grained assessments
and actionable revisions, and the actor to utilize these critiques, our
approach promotes more robust exploration of alternative strategies while
avoiding local optima. Experiments in three interactive environments show that
CGI outperforms existing baselines by a substantial margin. Notably, even a
small critic model surpasses GPT-4 in feedback quality. The resulting actor
achieves state-of-the-art performance, demonstrating the power of explicit
iterative guidance to enhance decision-making in LLM-based agents.
