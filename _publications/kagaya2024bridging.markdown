---
layout: publication
title: 'Envbridge: Bridging Diverse Environments With Cross-environment Knowledge Transfer For Embodied AI'
authors: Tomoyuki Kagaya, Yuxuan Lou, Thong Jing Yuan, Subramanian Lakshmi, Jayashree Karlekar, Sugiri Pranata, Natsuki Murakami, Akira Kinose, Koki Oguri, Felix Wick, Yang You
conference: "Arxiv"
year: 2024
bibkey: kagaya2024bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16919"}
tags: ['Agentic', 'Security', 'Model Architecture', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications', 'Attention Mechanism']
---
In recent years, Large Language Models (LLMs) have demonstrated high
reasoning capabilities, drawing attention for their applications as agents in
various decision-making processes. One notably promising application of LLM
agents is robotic manipulation. Recent research has shown that LLMs can
generate text planning or control code for robots, providing substantial
flexibility and interaction capabilities. However, these methods still face
challenges in terms of flexibility and applicability across different
environments, limiting their ability to adapt autonomously. Current approaches
typically fall into two categories: those relying on environment-specific
policy training, which restricts their transferability, and those generating
code actions based on fixed prompts, which leads to diminished performance when
confronted with new environments. These limitations significantly constrain the
generalizability of agents in robotic manipulation. To address these
limitations, we propose a novel method called EnvBridge. This approach involves
the retention and transfer of successful robot control codes from source
environments to target environments. EnvBridge enhances the agent's
adaptability and performance across diverse settings by leveraging insights
from multiple environments. Notably, our approach alleviates environmental
constraints, offering a more flexible and generalizable solution for robotic
manipulation tasks. We validated the effectiveness of our method using robotic
manipulation benchmarks: RLBench, MetaWorld, and CALVIN. Our experiments
demonstrate that LLM agents can successfully leverage diverse knowledge sources
to solve complex tasks. Consequently, our approach significantly enhances the
adaptability and robustness of robotic manipulation agents in planning across
diverse environments.
