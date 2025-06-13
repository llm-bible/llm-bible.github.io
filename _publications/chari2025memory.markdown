---
layout: publication
title: 'MINDSTORES: Memory-informed Neural Decision Synthesis For Task-oriented Reinforcement In Embodied Systems'
authors: Anirudh Chari, Suraj Reddy, Aditya Tiwari, Richard Lian, Brian Zhou
conference: "Arxiv"
year: 2025
bibkey: chari2025memory
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.19318'}
tags: ['Agentic', 'RAG', 'Security', 'Tools', 'Reinforcement Learning']
---
While large language models (LLMs) have shown promising capabilities as zero-shot planners for embodied agents, their inability to learn from experience and build persistent mental models limits their robustness in complex open-world environments like Minecraft. We introduce MINDSTORES, an experience-augmented planning framework that enables embodied agents to build and leverage mental models through natural interaction with their environment. Drawing inspiration from how humans construct and refine cognitive mental models, our approach extends existing zero-shot LLM planning by maintaining a database of past experiences that informs future planning iterations. The key innovation is representing accumulated experiences as natural language embeddings of (state, task, plan, outcome) tuples, which can then be efficiently retrieved and reasoned over by an LLM planner to generate insights and guide plan refinement for novel states and tasks. Through extensive experiments in the MineDojo environment, a simulation environment for agents in Minecraft that provides low-level controls for Minecraft, we find that MINDSTORES learns and applies its knowledge significantly better than existing memory-based LLM planners while maintaining the flexibility and generalization benefits of zero-shot approaches, representing an important step toward more capable embodied AI systems that can learn continuously through natural experience.
