---
layout: publication
title: 'Llm-assist: Enhancing Closed-loop Planning With Language-based Reasoning'
authors: S P Sharan, Francesco Pittaluga, Vijay Kumar B G, Manmohan Chandraker
conference: "Arxiv"
year: 2023
bibkey: sharan2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00125"}
  - {name: "Code", url: "https://llmassist.github.io"}
tags: ['RAG', 'Model Architecture', 'GPT', 'Has Code']
---
Although planning is a crucial component of the autonomous driving stack,
researchers have yet to develop robust planning algorithms that are capable of
safely handling the diverse range of possible driving scenarios. Learning-based
planners suffer from overfitting and poor long-tail performance. On the other
hand, rule-based planners generalize well, but might fail to handle scenarios
that require complex driving maneuvers. To address these limitations, we
investigate the possibility of leveraging the common-sense reasoning
capabilities of Large Language Models (LLMs) such as GPT4 and Llama2 to
generate plans for self-driving vehicles. In particular, we develop a novel
hybrid planner that leverages a conventional rule-based planner in conjunction
with an LLM-based planner. Guided by commonsense reasoning abilities of LLMs,
our approach navigates complex scenarios which existing planners struggle with,
produces well-reasoned outputs while also remaining grounded through working
alongside the rule-based approach. Through extensive evaluation on the nuPlan
benchmark, we achieve state-of-the-art performance, outperforming all existing
pure learning- and rule-based methods across most metrics. Our code will be
available at https://llmassist.github.io.
