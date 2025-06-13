---
layout: publication
title: 'Ecoact: Economic Agent Determines When To Register What Action'
authors: Shaokun Zhang, Jieyu Zhang, Dujian Ding, Mirian Hipolito Garcia, Ankur Mallick, Daniel Madrigal, Menglin Xia, Victor Rühle, Qingyun Wu, Chi Wang
conference: "Arxiv"
year: 2024
bibkey: zhang2024economic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01643"}
tags: ['Prompting', 'Agentic', 'Tools']
---
Recent advancements have enabled Large Language Models (LLMs) to function as
agents that can perform actions using external tools. This requires
registering, i.e., integrating tool information into the LLM context prior to
taking actions. Current methods indiscriminately incorporate all candidate
tools into the agent's context and retain them across multiple reasoning steps.
This process remains opaque to LLM agents and is not integrated into their
reasoning procedures, leading to inefficiencies due to increased context length
from irrelevant tools. To address this, we introduce EcoAct, a tool using
algorithm that allows LLMs to selectively register tools as needed, optimizing
context use. By integrating the tool registration process into the reasoning
procedure, EcoAct reduces computational costs by over 50% in multiple steps
reasoning tasks while maintaining performance, as demonstrated through
extensive experiments. Moreover, it can be plugged into any reasoning pipeline
with only minor modifications to the prompt, making it applicable to LLM agents
now and future.
