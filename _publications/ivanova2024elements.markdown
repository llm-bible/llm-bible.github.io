---
layout: publication
title: 'Elements Of World Knowledge (EWOK): A Cognition-inspired Framework For Evaluating Basic World Knowledge In Language Models'
authors: Ivanova Anna A., Sathe Aalok, Lipkin Benjamin, Kumar Unnathi, Radkani Setayesh, Clark Thomas H., Kauf Carina, Hu Jennifer, Pramod R. T., Grand Gabriel, Paulun Vivian, Ryskina Maria, Akyürek Ekin, Wilcox Ethan, Rashid Nafisa, Choshen Leshem, Levy Roger, Fedorenko Evelina, Tenenbaum Joshua, Andreas Jacob
conference: "Arxiv"
year: 2024
bibkey: ivanova2024elements
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.09605"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Tools', 'Uncategorized']
---
The ability to build and leverage world models is essential for a general-purpose AI agent. Testing such capabilities is hard, in part because the building blocks of world models are ill-defined. We present Elements of World Knowledge (EWOK), a framework for evaluating world modeling in language models by testing their ability to use knowledge of a concept to match a target text with a plausible/implausible context. EWOK targets specific concepts from multiple knowledge domains known to be vital for world modeling in humans. Domains range from social interactions (help/hinder) to spatial relations (left/right). Both, contexts and targets are minimal pairs. Objects, agents, and locations in the items can be flexibly filled in enabling easy generation of multiple controlled datasets. We then introduce EWOK-CORE-1.0, a dataset of 4,374 items covering 11 world knowledge domains. We evaluate 20 openweights large language models (1.3B--70B parameters) across a battery of evaluation paradigms along with a human norming study comprising 12,480 measurements. The overall performance of all tested models is worse than human performance, with results varying drastically across domains. These data highlight simple cases where even large models fail and present rich avenues for targeted research on LLM world modeling capabilities.
