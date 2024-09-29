---
layout: publication
title: Input Conditioned Graph Generation For Language Agents
authors: Vierling Lukas, Fu Jie, Chen Kai
conference: "Arxiv"
year: 2024
bibkey: vierling2024input
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11555"}
  - {name: "Code", url: "https://github.com/lukasVierling/DynamicGPTSwarm"}
tags: ['Agentic', 'Applications', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent progress in Large Language Models (LLMs) and language agents has demonstrated significant promise for various future applications across multiple disciplines. While traditional approaches to language agents often rely on fixed handcrafted designs our research aims to develop both learnable and dynamic agents. Our method uses an existing framework that abstracts language agents as graphs. Within this graph framework we aim to learn a model that can generate edges for every given input to the language agent. This allows us to generate edges that represent the flow of communication within the graph based on the given input thereby adjusting the internal communication of a language agent. We learn to generate these edges using a pretrained LLM that is fine-tuned with reinforcement learning. This LLM can be fine-tuned on several datasets simultaneously and we hypothesize that the model learns to adapt to these different domains during training achieving good overall performance when encountering data from different domains during deployment. We demonstrate that our approach surpasses the previous static approach by nearly 637; accuracy on a combined dataset of MMLU and CMMLU and by more than 1037; when trained with a sparsity-inducing loss. It also performs superior in additional experiments conducted with the MMLU and Mini Crossword Puzzles datasets. The code is available at https://github.com/lukasVierling/DynamicGPTSwarm.
