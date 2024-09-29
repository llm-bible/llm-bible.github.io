---
layout: publication
title: Activation Addition\: Steering Language Models Without Optimization
authors: Turner Alexander Matt, Thiergart Lisa, Leech Gavin, Udell David, Vazquez Juan J., Mini Ulisse, Macdiarmid Monte
conference: "Arxiv"
year: 2023
bibkey: turner2023activation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.10248"}
tags: ['Agentic', 'Efficiency And Optimization', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Reliably controlling the behavior of large language models is a pressing open problem. Existing methods include supervised finetuning reinforcement learning from human feedback prompt engineering and guided decoding. We instead investigate activation engineering modifying activations at inference-time to predictably alter model behavior. We bias the forward pass with a steering vector implicitly specified through natural language. Past work learned these steering vectors; our Activation Addition (ActAdd) method instead computes them by taking activation differences resulting from pairs of prompts. We demonstrate ActAdd on a range of LLMs (LLaMA-3 OPT GPT-2 and GPT-J) obtaining SOTA on detoxification and negative-to-positive sentiment control. Our approach yields inference-time control over high-level properties of output like topic and sentiment while preserving performance on off-target tasks. ActAdd takes far less compute and implementation effort than finetuning or RLHF allows users control through natural language and its computational overhead (as a fraction of inference time) appears stable or improving over increasing model size.
