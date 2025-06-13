---
layout: publication
title: 'Critic-cot: Boosting The Reasoning Abilities Of Large Language Model Via Chain-of-thoughts Critic'
authors: Xin Zheng, Jie Lou, Boxi Cao, Xueru Wen, Yuqiu Ji, Hongyu Lin, Yaojie Lu, Xianpei Han, Debing Zhang, Le Sun
conference: "Arxiv"
year: 2024
bibkey: zheng2024critic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16326"}
tags: ['Prompting', 'Tools']
---
Self-critic has become a crucial mechanism for enhancing the reasoning
performance of LLMs. However, current approaches mainly involve basic prompts
for intuitive instance-level feedback, which resembles System-1 processes and
limits the reasoning capabilities. Moreover, there is a lack of in-depth
investigations into the relationship between LLM's ability to criticize and its
task-solving performance. To address these issues, we propose Critic-CoT, a
novel framework that pushes LLMs toward System-2-like critic capability.
Through a step-wise CoT reasoning paradigm and the automatic construction of
distant-supervision data without human annotation, Critic-CoT enables LLMs to
engage in slow, analytic self-critique and refinement, thereby improving their
reasoning abilities. Experiments on GSM8K and MATH demonstrate that our
enhanced model significantly boosts task-solving performance by filtering out
invalid solutions or iterative refinement. Furthermore, we investigate the
intrinsic correlation between critique and task-solving abilities within LLMs,
discovering that these abilities can mutually reinforce each other rather than
conflict.
