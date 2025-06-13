---
layout: publication
title: 'PRL: Prompts From Reinforcement Learning'
authors: Paweł Batorski, Adrian Kosmala, Paul Swoboda
conference: "Arxiv"
year: 2025
bibkey: batorski2025prompts
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14412"}
  - {name: "Code", url: "https://github.com/Batorskq/prl"}
tags: ['Agentic', 'Training Techniques', 'Few-Shot', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting', 'Applications']
---
Effective prompt engineering remains a central challenge in fully harnessing the capabilities of LLMs. While well-designed prompts can dramatically enhance performance, crafting them typically demands expert intuition and a nuanced understanding of the task. Moreover, the most impactful prompts often hinge on subtle semantic cues, ones that may elude human perception but are crucial for guiding LLM behavior. In this paper, we introduce PRL (Prompts from Reinforcement Learning), a novel RL-based approach for automatic prompt generation. Unlike previous methods, PRL can produce novel few-shot examples that were not seen during training. Our approach achieves state-of-the-art performance across a range of benchmarks, including text classification, simplification, and summarization. On the classification task, it surpasses prior methods by 2.58% over APE and 1.00% over EvoPrompt. Additionally, it improves the average ROUGE scores on the summarization task by 4.32 over APE and by 2.12 over EvoPrompt and the SARI score on simplification by 6.93 over APE and by 6.01 over EvoPrompt. Our code is available at https://github.com/Batorskq/prl .
