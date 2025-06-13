---
layout: publication
title: 'Towards Conversational AI For Human-machine Collaborative Mlops'
authors: George Fatouros, Georgios Makridis, George Kousiouris, John Soldatos, Anargyros Tsadimas, Dimosthenis Kyriazis
conference: "Arxiv"
year: 2025
bibkey: fatouros2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12477'}
tags: ['RAG', 'Model Architecture', 'Agentic', 'Tools']
---
This paper presents a Large Language Model (LLM) based conversational agent
system designed to enhance human-machine collaboration in Machine Learning
Operations (MLOps). We introduce the Swarm Agent, an extensible architecture
that integrates specialized agents to create and manage ML workflows through
natural language interactions. The system leverages a hierarchical, modular
design incorporating a KubeFlow Pipelines (KFP) Agent for ML pipeline
orchestration, a MinIO Agent for data management, and a Retrieval-Augmented
Generation (RAG) Agent for domain-specific knowledge integration. Through
iterative reasoning loops and context-aware processing, the system enables
users with varying technical backgrounds to discover, execute, and monitor ML
pipelines; manage datasets and artifacts; and access relevant documentation,
all via intuitive conversational interfaces. Our approach addresses the
accessibility gap in complex MLOps platforms like Kubeflow, making advanced ML
tools broadly accessible while maintaining the flexibility to extend to other
platforms. The paper describes the architecture, implementation details, and
demonstrates how this conversational MLOps assistant reduces complexity and
lowers barriers to entry for users across diverse technical skill levels.
