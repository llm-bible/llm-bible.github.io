---
layout: publication
title: 'Leanabell-prover: Posttraining Scaling In Formal Reasoning'
authors: Jingyuan Zhang, Qi Wang, Xingguang Ji, Yahui Liu, Yang Yue, Fuzheng Zhang, Di Zhang, Guorui Zhou, Kun Gai
conference: "Arxiv"
year: 2025
bibkey: zhang2025leanabell
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.06122'}
tags: ['Reinforcement Learning', 'Agentic', 'Training Techniques']
---
Recent advances in automated theorem proving (ATP) through LLMs have
highlighted the potential of formal reasoning with Lean 4 codes. However, ATP
has not yet be revolutionized by the recent posttraining scaling as
demonstrated by Open AI O1/O3 and Deepseek R1. In this work, we investigate the
entire posttraining of ATP, aiming to align it with breakthroughs in reasoning
models in natural languages. To begin, we continual train current ATP models
with a hybrid dataset, which consists of numerous statement-proof pairs, and
additional data aimed at incorporating cognitive behaviors that emulate human
reasoning and hypothesis refinement. Next, we explore reinforcement learning
with the use of outcome reward returned by Lean 4 compiler. Through our
designed continual training and reinforcement learning processes, we have
successfully improved existing formal provers, including both
DeepSeek-Prover-v1.5 and Goedel-Prover, achieving state-of-the-art performance
in the field of whole-proof generation. For example, we achieve a 59.8% pass
rate (pass@32) on MiniF2F. This is an on-going project and we will
progressively update our findings, release our data and training details.
