---
layout: publication
title: AMERICANO Argument Generation with Discourse-driven Decomposition and Agent Interaction
authors: Hu Zhe, Chan Hou Pong, Yin Yu
conference: "Arxiv"
year: 2023
bibkey: hu2023americano
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20352"}
tags: ['Agentic', 'GPT', 'Pretraining Methods', 'Prompting', 'Tools']
---
Argument generation is a challenging task in natural language processing which requires rigorous reasoning and proper content organization. Inspired by recent chain-of-thought prompting that breaks down a complex task into intermediate steps we propose Americano a novel framework with agent interaction for argument generation. Our approach decomposes the generation process into sequential actions grounded on argumentation theory which first executes actions sequentially to generate argumentative discourse components and then produces a final argument conditioned on the components. To further mimic the human writing process and improve the left-to-right generation paradigm of current autoregressive language models we introduce an argument refinement module which automatically evaluates and refines argument drafts based on feedback received. We evaluate our framework on the task of counterargument generation using a subset of Reddit/CMV dataset. The results show that our method outperforms both end-to-end and chain-of-thought prompting methods and can generate more coherent and persuasive arguments with diverse and rich contents.
