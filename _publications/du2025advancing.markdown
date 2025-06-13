---
layout: publication
title: 'Advancing LLM Safe Alignment With Safety Representation Ranking'
authors: Tianqi Du, Zeming Wei, Quan Chen, Chenheng Zhang, Yisen Wang
conference: "Arxiv"
year: 2025
bibkey: du2025advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15710"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Transformer', 'Prompting']
---
The rapid advancement of large language models (LLMs) has demonstrated milestone success in a variety of tasks, yet their potential for generating harmful content has raised significant safety concerns. Existing safety evaluation approaches typically operate directly on textual responses, overlooking the rich information embedded in the model's internal representations. In this paper, we propose Safety Representation Ranking (SRR), a listwise ranking framework that selects safe responses using hidden states from the LLM itself. SRR encodes both instructions and candidate completions using intermediate transformer representations and ranks candidates via a lightweight similarity-based scorer. Our approach directly leverages internal model states and supervision at the list level to capture subtle safety signals. Experiments across multiple benchmarks show that SRR significantly improves robustness to adversarial prompts. Our code will be available upon publication.
