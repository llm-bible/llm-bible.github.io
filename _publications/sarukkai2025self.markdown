---
layout: publication
title: 'Self-generated In-context Examples Improve LLM Agents For Sequential Decision-making Tasks'
authors: Vishnu Sarukkai, Zhiqiang Xie, Kayvon Fatahalian
conference: "Arxiv"
year: 2025
bibkey: sarukkai2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00234"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Prompting']
---
Improving Large Language Model (LLM) agents for sequential decision-making tasks typically requires extensive task-specific knowledge engineering--custom prompts, curated examples, and specialized observation/action spaces. We investigate a different approach where agents automatically improve by learning from their own successful experiences without human intervention. Our method constructs and refines a database of self-generated trajectories that serve as in-context examples for future tasks. Even naive accumulation of successful trajectories yields substantial performance gains across three diverse benchmarks: ALFWorld (73% to 89%), Wordcraft (55% to 64%), and InterCode-SQL (75% to 79%). These improvements exceed those achieved by upgrading from gpt-4o-mini to gpt-4o and match the performance of allowing multiple attempts per task. We further enhance this approach with two innovations: database-level curation using population-based training to propagate high-performing example collections, and exemplar-level curation that selectively retains trajectories based on their empirical utility as in-context examples. With these enhancements, our method achieves 93% success on ALFWorld--surpassing approaches that use more powerful LLMs and hand-crafted components. Our trajectory bootstrapping technique demonstrates that agents can autonomously improve through experience, offering a scalable alternative to labor-intensive knowledge engineering.
