---
layout: publication
title: 'Exploring How Llms Capture And Represent Domain-specific Knowledge'
authors: Mirian Hipolito Garcia, Camille Couturier, Daniel Madrigal Diaz, Ankur Mallick, Anastasios Kyrillidis, Robert Sim, Victor Ruhle, Saravan Rajmohan
conference: "Arxiv"
year: 2025
bibkey: garcia2025exploring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.16871'}
tags: ['RAG', 'Prompting', 'Security']
---
We study whether Large Language Models (LLMs) inherently capture
domain-specific nuances in natural language. Our experiments probe the domain
sensitivity of LLMs by examining their ability to distinguish queries from
different domains using hidden states generated during the prefill phase. We
reveal latent domain-related trajectories that indicate the model's internal
recognition of query domains. We also study the robustness of these domain
representations to variations in prompt styles and sources. Our approach
leverages these representations for model selection, mapping the LLM that best
matches the domain trace of the input query (i.e., the model with the highest
performance on similar traces). Our findings show that LLMs can differentiate
queries for related domains, and that the fine-tuned model is not always the
most accurate. Unlike previous work, our interpretations apply to both closed
and open-ended generative tasks
