---
layout: publication
title: 'Dicore: Enhancing Zero-shot Event Detection Via Divergent-convergent LLM Reasoning'
authors: Tanmay Parekh, Kartik Mehta, Ninareh Mehrabi, Kai-wei Chang, Nanyun Peng
conference: "Arxiv"
year: 2025
bibkey: parekh2025enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.05128'}
tags: ['Training Techniques', 'RAG', 'Reinforcement Learning', 'Tools']
---
Zero-shot Event Detection (ED), the task of identifying event mentions in natural language text without any training data, is critical for document understanding in specialized domains. Understanding the complex event ontology, extracting domain-specific triggers from the passage, and structuring them appropriately overloads and limits the utility of Large Language Models (LLMs) for zero-shot ED. To this end, we propose DiCoRe, a divergent-convergent reasoning framework that decouples the task of ED using Dreamer and Grounder. Dreamer encourages divergent reasoning through open-ended event discovery, which helps to boost event coverage. Conversely, Grounder introduces convergent reasoning to align the free-form predictions with the task-specific instructions using finite-state machine guided constrained decoding. Additionally, an LLM-Judge verifies the final outputs to ensure high precision. Through extensive experiments on six datasets across five domains and nine LLMs, we demonstrate how DiCoRe consistently outperforms prior zero-shot, transfer-learning, and reasoning baselines, achieving 4-7% average F1 gains over the best baseline -- establishing DiCoRe as a strong zero-shot ED framework.
