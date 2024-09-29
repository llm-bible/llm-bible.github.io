---
layout: publication
title: Instruction45;following Agents With Multimodal Transformer
authors: Liu Hao, Lee Lisa, Lee Kimin, Abbeel Pieter
conference: "Arxiv"
year: 2022
bibkey: liu2022instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.13431"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Transformer']
---
Humans are excellent at understanding language and vision to accomplish a wide range of tasks. In contrast creating general instruction45;following embodied agents remains a difficult challenge. Prior work that uses pure language45;only models lack visual grounding making it difficult to connect language instructions with visual observations. On the other hand methods that use pre45;trained multimodal models typically come with divided language and visual representations requiring designing specialized network architecture to fuse them together. We propose a simple yet effective model for robots to solve instruction45;following tasks in vision45;based environments. Our ours method consists of a multimodal transformer that encodes visual observations and language instructions and a transformer45;based policy that predicts actions based on encoded representations. The multimodal transformer is pre45;trained on millions of image45;text pairs and natural language text thereby producing generic cross45;modal representations of observations and instructions. The transformer45;based policy keeps track of the full history of observations and actions and predicts actions autoregressively. Despite its simplicity we show that this unified transformer model outperforms all state45;of45;the45;art pre45;trained or trained45;from45;scratch methods in both single45;task and multi45;task settings. Our model also shows better model scalability and generalization ability than prior work.
