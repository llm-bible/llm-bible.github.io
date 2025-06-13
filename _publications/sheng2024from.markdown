---
layout: publication
title: 'From Language Models To Practical Self-improving Computer Agents'
authors: Alex Sheng
conference: "Arxiv"
year: 2024
bibkey: sheng2024from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.11964'}
tags: ['Reinforcement Learning', 'Prompting', 'Agentic', 'Tools']
---
We develop a simple and straightforward methodology to create AI computer
agents that can carry out diverse computer tasks and self-improve by developing
tools and augmentations to enable themselves to solve increasingly complex
tasks. As large language models (LLMs) have been shown to benefit from
non-parametric augmentations, a significant body of recent work has focused on
developing software that augments LLMs with various capabilities. Rather than
manually developing static software to augment LLMs through human engineering
effort, we propose that an LLM agent can systematically generate software to
augment itself. We show, through a few case studies, that a minimal querying
loop with appropriate prompt engineering allows an LLM to generate and use
various augmentations, freely extending its own capabilities to carry out
real-world computer tasks. Starting with only terminal access, we prompt an LLM
agent to augment itself with retrieval, internet search, web navigation, and
text editor capabilities. The agent effectively uses these various tools to
solve problems including automated software development and web-based tasks.
