---
layout: publication
title: 'Ghost In The Minecraft: Generally Capable Agents For Open-world Environments
  Via Large Language Models With Text-based Knowledge And Memory'
authors: Xizhou Zhu et al.
conference: Arxiv
year: 2023
citations: 17
bibkey: zhu2023ghost
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.17144'}, {name: Code,
    url: 'https://github.com/OpenGVLab/GITM'}]
tags: [RAG, Agentic, Reinforcement Learning]
---
The captivating realm of Minecraft has attracted substantial research
interest in recent years, serving as a rich platform for developing intelligent
agents capable of functioning in open-world environments. However, the current
research landscape predominantly focuses on specific objectives, such as the
popular "ObtainDiamond" task, and has not yet shown effective generalization to
a broader spectrum of tasks. Furthermore, the current leading success rate for
the "ObtainDiamond" task stands at around 20%, highlighting the limitations of
Reinforcement Learning (RL) based controllers used in existing methods. To
tackle these challenges, we introduce Ghost in the Minecraft (GITM), a novel
framework integrates Large Language Models (LLMs) with text-based knowledge and
memory, aiming to create Generally Capable Agents (GCAs) in Minecraft. These
agents, equipped with the logic and common sense capabilities of LLMs, can
skillfully navigate complex, sparse-reward environments with text-based
interactions. We develop a set of structured actions and leverage LLMs to
generate action plans for the agents to execute. The resulting LLM-based agent
markedly surpasses previous methods, achieving a remarkable improvement of
+47.5% in success rate on the "ObtainDiamond" task, demonstrating superior
robustness compared to traditional RL-based controllers. Notably, our agent is
the first to procure all items in the Minecraft Overworld technology tree,
demonstrating its extensive capabilities. GITM does not need any GPU for
training, but a single CPU node with 32 CPU cores is enough. This research
shows the potential of LLMs in developing capable agents for handling
long-horizon, complex tasks and adapting to uncertainties in open-world
environments. See the project website at https://github.com/OpenGVLab/GITM.