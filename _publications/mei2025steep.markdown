---
layout: publication
title: 'A1: Steep Test-time Scaling Law Via Environment Augmented Generation'
authors: Lingrui Mei, Shenghua Liu, Yiwei Wang, Baolong Bi, Yuyao Ge, Jun Wan, Yurong Wu, Xueqi Cheng
conference: "Arxiv"
year: 2025
bibkey: mei2025steep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14597"}
tags: ['Prompting', 'Fine-Tuning', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) have made remarkable breakthroughs in reasoning,
yet continue to struggle with hallucinations, logical errors, and inability to
self-correct during complex multi-step tasks. Current approaches like
chain-of-thought prompting offer limited reasoning capabilities that fail when
precise step validation is required. We propose Environment Augmented
Generation (EAG), a framework that enhances LLM reasoning through: (1)
real-time environmental feedback validating each reasoning step, (2) dynamic
branch exploration for investigating alternative solution paths when faced with
errors, and (3) experience-based learning from successful reasoning
trajectories. Unlike existing methods, EAG enables deliberate backtracking and
strategic replanning through tight integration of execution feedback with
branching exploration. Our a1-32B model achieves state-of-the-art performance
among similar-sized models across all benchmarks, matching larger models like
o1 on competition mathematics while outperforming comparable models by up to
24.4 percentage points. Analysis reveals EAG's distinctive scaling pattern:
initial token investment in environment interaction yields substantial
long-term performance dividends, with advantages amplifying proportionally to
task complexity. EAG's theoretical framework demonstrates how environment
interactivity and systematic branch exploration together establish a new
paradigm for reliable machine reasoning, particularly for problems requiring
precise multi-step calculation and logical verification.
