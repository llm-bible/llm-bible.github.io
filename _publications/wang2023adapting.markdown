---
layout: publication
title: 'Adapting LLM Agents With Universal Feedback In Communication'
authors: Kuan Wang, Yadong Lu, Michael Santacroce, Yeyun Gong, Chao Zhang, Yelong Shen
conference: "Arxiv"
year: 2023
bibkey: wang2023adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01444"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Recent advances in large language models (LLMs) have demonstrated potential
for LLM agents. To facilitate the training for these agents with both
linguistic feedback and non-linguistic reward signals, we introduce Learning
through Communication (LTC). We design a universal buffer to store all the
feedback, and an iterative pipeline to enable an LLM agent to explore and
update its policy in an given environment. To optimize agent interactions for
task-specific learning with our universal buffer and pipeline, we introduce
diverse communication patterns tailored for both single-agent and multi-agent
environments. We evaluate the efficacy of our LTC approach on four diverse
datasets: ALFWorld (single-agent), HotpotQA (multi-agent collaboration),
Chameleon (multi-agent competition), and GSM8k (multi-agent teacher-student).
On these data sets, LTC outperforms the supervised instruction fine-tuning
baselines by 3.6% to 12%. These results highlight the versatility and
efficiency of LTC in facilitating online adaptation for LLM agents.
