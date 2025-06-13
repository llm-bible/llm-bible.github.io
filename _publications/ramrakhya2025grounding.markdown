---
layout: publication
title: 'Grounding Multimodal Llms To Embodied Agents That Ask For Help With Reinforcement Learning'
authors: Ram Ramrakhya, Matthew Chang, Xavier Puig, Ruta Desai, Zsolt Kira, Roozbeh Mottaghi
conference: "Arxiv"
year: 2025
bibkey: ramrakhya2025grounding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.00907"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models']
---
Embodied agents operating in real-world environments must interpret ambiguous
and under-specified human instructions. A capable household robot should
recognize ambiguity and ask relevant clarification questions to infer the user
intent accurately, leading to more effective task execution. To study this
problem, we introduce the Ask-to-Act task, where an embodied agent must fetch a
specific object instance given an ambiguous instruction in a home environment.
The agent must strategically ask minimal, yet relevant, clarification questions
to resolve ambiguity while navigating under partial observability. To solve
this problem, we propose a novel approach that fine-tunes multimodal large
language models (MLLMs) as vision-language-action (VLA) policies using online
reinforcement learning (RL) with LLM-generated rewards. Our method eliminates
the need for large-scale human demonstrations or manually engineered rewards
for training such agents. We benchmark against strong zero-shot baselines,
including GPT-4o, and supervised fine-tuned MLLMs, on our task. Our results
demonstrate that our RL-finetuned MLLM outperforms all baselines by a
significant margin (\\(19.1\\)-\\(40.3%\\)), generalizing well to novel scenes and
tasks. To the best of our knowledge, this is the first demonstration of
adapting MLLMs as VLA agents that can act and ask for help using LLM-generated
rewards with online RL.
