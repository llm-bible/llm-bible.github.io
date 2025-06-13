---
layout: publication
title: 'Factored Agents: Decoupling In-context Learning And Memorization For Robust Tool Use'
authors: Nicholas Roth, Christopher Hidey, Lucas Spangher, William F. Arnold, Chang Ye, Nick Masiewicki, Jinoo Baek, Peter Grabowski, Eugene Ie
conference: "Arxiv"
year: 2025
bibkey: roth2025factored
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22931"}
tags: ['Agentic', 'Tools', 'Model Architecture', 'Prompting', 'In-Context Learning']
---
In this paper, we propose a novel factored agent architecture designed to
overcome the limitations of traditional single-agent systems in agentic AI. Our
approach decomposes the agent into two specialized components: (1) a large
language model (LLM) that serves as a high level planner and in-context
learner, which may use dynamically available information in user prompts, (2) a
smaller language model which acts as a memorizer of tool format and output.
This decoupling addresses prevalent issues in monolithic designs, including
malformed, missing, and hallucinated API fields, as well as suboptimal planning
in dynamic environments. Empirical evaluations demonstrate that our factored
architecture significantly improves planning accuracy and error resilience,
while elucidating the inherent trade-off between in-context learning and static
memorization. These findings suggest that a factored approach is a promising
pathway for developing more robust and adaptable agentic AI systems.
