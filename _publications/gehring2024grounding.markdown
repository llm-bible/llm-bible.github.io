---
layout: publication
title: 'RLEF: Grounding Code Llms In Execution Feedback With Reinforcement Learning'
authors: Jonas Gehring, Kunhao Zheng, Jade Copet, Vegard Mella, Quentin Carbonneaux, Taco Cohen, Gabriel Synnaeve
conference: "Arxiv"
year: 2024
bibkey: gehring2024grounding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02089'}
tags: ['Reinforcement Learning', 'RAG', 'Agentic']
---
Large language models (LLMs) deployed as agents solve user-specified tasks
over multiple steps while keeping the required manual engagement to a minimum.
Crucially, such LLMs need to ground their generations in any feedback obtained
to reliably achieve the desired outcomes. We propose an end-to-end
reinforcement learning method for teaching models to leverage execution
feedback in the realm of code synthesis, where state-of-the-art LLMs struggle
to improve code iteratively compared to independent sampling. We benchmark on
competitive programming tasks, where we achieve new state-of-the art results
with both small (8B parameters) and large (70B) models while reducing the
amount of samples required by an order of magnitude. Our analysis of
inference-time behavior demonstrates that our method produces LLMs that
effectively leverage automatic feedback over multiple steps.
