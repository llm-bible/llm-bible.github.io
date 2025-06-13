---
layout: publication
title: 'Online Preference-based Reinforcement Learning With Self-augmented Feedback From Large Language Model'
authors: Songjun Tu, Jingbo Sun, Qichao Zhang, Xiangyuan Lan, Dongbin Zhao
conference: "The 24th International Conference on Autonomous Agents and Multi-Agent Systems AAMAS-2025"
year: 2024
bibkey: tu2024online
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16878"}
tags: ['RAG', 'Agentic', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Preference-based reinforcement learning (PbRL) provides a powerful paradigm
to avoid meticulous reward engineering by learning rewards based on human
preferences. However, real-time human feedback is hard to obtain in online
tasks. Most work suppose there is a "scripted teacher" that utilizes privileged
predefined reward to provide preference feedback. In this paper, we propose a
RL Self-augmented Large Language Model Feedback (RL-SaLLM-F) technique that
does not rely on privileged information for online PbRL. RL-SaLLM-F leverages
the reflective and discriminative capabilities of LLM to generate
self-augmented trajectories and provide preference labels for reward learning.
First, we identify an failure issue in LLM-based preference discrimination,
specifically "query ambiguity", in online PbRL. Then LLM is employed to provide
preference labels and generate self-augmented imagined trajectories that better
achieve the task goal, thereby enhancing the quality and efficiency of
feedback. Additionally, a double-check mechanism is introduced to mitigate
randomness in the preference labels, improving the reliability of LLM feedback.
The experiment across multiple tasks in the MetaWorld benchmark demonstrates
the specific contributions of each proposed module in RL-SaLLM-F, and shows
that self-augmented LLM feedback can effectively replace the impractical
"scripted teacher" feedback. In summary, RL-SaLLM-F introduces a new direction
of feedback acquisition in online PbRL that does not rely on any online
privileged information, offering an efficient and lightweight solution with
LLM-driven feedback.
