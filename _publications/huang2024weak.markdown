---
layout: publication
title: 'WESE: Weak Exploration To Strong Exploitation For LLM Agents'
authors: Xu Huang, Weiwen Liu, Xiaolong Chen, Xingmei Wang, Defu Lian, Yasheng Wang, Ruiming Tang, Enhong Chen
conference: "Arxiv"
year: 2024
bibkey: huang2024weak
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.07456'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Recently, large language models (LLMs) have demonstrated remarkable potential
as an intelligent agent. However, existing researches mainly focus on enhancing
the agent's reasoning or decision-making abilities through well-designed prompt
engineering or task-specific fine-tuning, ignoring the procedure of exploration
and exploitation. When addressing complex tasks within open-world interactive
environments, these methods exhibit limitations. Firstly, the lack of global
information of environments leads to greedy decisions, resulting in sub-optimal
solutions. On the other hand, irrelevant information acquired from the
environment not only adversely introduces noise, but also incurs additional
cost. This paper proposes a novel approach, Weak Exploration to Strong
Exploitation (WESE), to enhance LLM agents in solving open-world interactive
tasks. Concretely, WESE involves decoupling the exploration and exploitation
process, employing a cost-effective weak agent to perform exploration tasks for
global knowledge. A knowledge graph-based strategy is then introduced to store
the acquired knowledge and extract task-relevant knowledge, enhancing the
stronger agent in success rate and efficiency for the exploitation task. Our
approach is flexible enough to incorporate diverse tasks, and obtains
significant improvements in both success rates and efficiency across four
interactive benchmarks.
