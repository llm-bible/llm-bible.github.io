---
layout: publication
title: 'Beyond Static Evaluation: A Dynamic Approach To Assessing AI Assistants'' API Invocation Capabilities'
authors: Honglin Mu, Yang Xu, Yunlong Feng, Xiaofeng Han, Yitong Li, Yutai Hou, Wanxiang Che
conference: "Arxiv"
year: 2024
bibkey: mu2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11128"}
tags: ['Tools', 'Agentic', 'Reinforcement Learning']
---
With the rise of Large Language Models (LLMs), AI assistants' ability to
utilize tools, especially through API calls, has advanced notably. This
progress has necessitated more accurate evaluation methods. Many existing
studies adopt static evaluation, where they assess AI assistants' API call
based on pre-defined dialogue histories. However, such evaluation method can be
misleading, as an AI assistant might fail in generating API calls from
preceding human interaction in real cases. Instead of the resource-intensive
method of direct human-machine interactions, we propose Automated Dynamic
Evaluation (AutoDE) to assess an assistant's API call capability without human
involvement. In our framework, we endeavor to closely mirror genuine human
conversation patterns in human-machine interactions, using a LLM-based user
agent, equipped with a user script to ensure human alignment. Experimental
results highlight that AutoDE uncovers errors overlooked by static evaluations,
aligning more closely with human assessment. Testing four AI assistants using
our crafted benchmark, our method further mirrored human evaluation compared to
conventional static evaluations.
