---
layout: publication
title: 'CAPO: Cost-aware Prompt Optimization'
authors: Tom Zehle, Moritz Schlager, Timo Heiß, Matthias Feurer
conference: "Arxiv"
year: 2025
bibkey: zehle2025cost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16005"}
tags: ['Efficiency and Optimization', 'RAG', 'Security', 'Few-Shot', 'Prompting']
---
Large language models (LLMs) have revolutionized natural language processing
by solving a wide range of tasks simply guided by a prompt. Yet their
performance is highly sensitive to prompt formulation. While automated prompt
optimization addresses this challenge by finding optimal prompts, current
methods require a substantial number of LLM calls and input tokens, making
prompt optimization expensive. We introduce CAPO (Cost-Aware Prompt
Optimization), an algorithm that enhances prompt optimization efficiency by
integrating AutoML techniques. CAPO is an evolutionary approach with LLMs as
operators, incorporating racing to save evaluations and multi-objective
optimization to balance performance with prompt length. It jointly optimizes
instructions and few-shot examples while leveraging task descriptions for
improved robustness. Our extensive experiments across diverse datasets and LLMs
demonstrate that CAPO outperforms state-of-the-art discrete prompt optimization
methods in 11/15 cases with improvements up to 21%p. Our algorithm achieves
better performances already with smaller budgets, saves evaluations through
racing, and decreases average prompt length via a length penalty, making it
both cost-efficient and cost-aware. Even without few-shot examples, CAPO
outperforms its competitors and generally remains robust to initial prompts.
CAPO represents an important step toward making prompt optimization more
powerful and accessible by improving cost-efficiency.
