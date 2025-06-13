---
layout: publication
title: 'CAAP: Context-aware Action Planning Prompting To Solve Computer Tasks With Front-end UI Only'
authors: Junhee Cho, Jihoon Kim, Daseul Bae, Jinho Choo, Youngjune Gwon, Yeong-dae Kwon
conference: "Arxiv"
year: 2024
bibkey: cho2024context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06947"}
  - {name: "Code", url: "https://github.com/caap-agent/caap-agent"}
tags: ['Agentic', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Prompting']
---
Software robots have long been used in Robotic Process Automation (RPA) to
automate mundane and repetitive computer tasks. With the advent of Large
Language Models (LLMs) and their advanced reasoning capabilities, these agents
are now able to handle more complex or previously unseen tasks. However,
LLM-based automation techniques in recent literature frequently rely on HTML
source code for input or application-specific API calls for actions, limiting
their applicability to specific environments. We propose an LLM-based agent
that mimics human behavior in solving computer tasks. It perceives its
environment solely through screenshot images, which are then converted into
text for an LLM to process. By leveraging the reasoning capability of the LLM,
we eliminate the need for large-scale human demonstration data typically
required for model training. The agent only executes keyboard and mouse
operations on Graphical User Interface (GUI), removing the need for
pre-provided APIs to function. To further enhance the agent's performance in
this setting, we propose a novel prompting strategy called Context-Aware Action
Planning (CAAP) prompting, which enables the agent to thoroughly examine the
task context from multiple perspectives. Our agent achieves an average success
rate of 94.5% on MiniWoB++ and an average task score of 62.3 on WebShop,
outperforming all previous studies of agents that rely solely on screen images.
This method demonstrates potential for broader applications, particularly for
tasks requiring coordination across multiple applications on desktops or
smartphones, marking a significant advancement in the field of automation
agents. Codes and models are accessible at
https://github.com/caap-agent/caap-agent.
