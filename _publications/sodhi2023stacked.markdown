---
layout: publication
title: 'Step: Stacked LLM Policies For Web Actions'
authors: Sodhi Paloma, Branavan S. R. K., Artzi Yoav, Mcdonald Ryan
conference: "Arxiv"
year: 2023
bibkey: sodhi2023stacked
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03720"}
  - {name: "Code", url: "https://asappresearch.github.io/webagents-step"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Performing tasks on the web presents fundamental challenges to large language models (LLMs), including combinatorially large open-world tasks and variations across web interfaces. Simply specifying a large prompt to handle all possible behaviors and states is extremely complex, and results in behavior leaks between unrelated behaviors. Decomposition to distinct policies can address this challenge, but requires carefully handing off control between policies. We propose Stacked LLM Policies for Web Actions (SteP), an approach to dynamically compose policies to solve a diverse set of web tasks. SteP defines a Markov Decision Process where the state is a stack of policies representing the control state, i.e., the chain of policy calls. Unlike traditional methods that are restricted to static hierarchies, SteP enables dynamic control that adapts to the complexity of the task. We evaluate SteP against multiple baselines and web environments including WebArena, MiniWoB++, and a CRM. On WebArena, SteP improves (14.9\&#37; to 33.5\&#37;) over SOTA that use GPT-4 policies, while on MiniWob++, SteP is competitive with prior works while using significantly less data. Our code and data are available at https://asappresearch.github.io/webagents-step.
