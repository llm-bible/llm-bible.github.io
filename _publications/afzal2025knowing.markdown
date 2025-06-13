---
layout: publication
title: 'Knowing Before Saying: LLM Representations Encode Information About Chain-of-thought Success Before Completion'
authors: Anum Afzal, Florian Matthes, Gal Chechik, Yftah Ziser
conference: "Arxiv"
year: 2025
bibkey: afzal2025knowing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24362"}
tags: ['Agentic', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'BERT']
---
We investigate whether the success of a zero-shot Chain-of-Thought (CoT) process can be predicted before completion. We discover that a probing classifier, based on LLM representations, performs well *even before a single token is generated*, suggesting that crucial information about the reasoning process is already present in the initial steps representations. In contrast, a strong BERT-based baseline, which relies solely on the generated tokens, performs worse, likely because it depends on shallow linguistic cues rather than deeper reasoning dynamics. Surprisingly, using later reasoning steps does not always improve classification. When additional context is unhelpful, earlier representations resemble later ones more, suggesting LLMs encode key information early. This implies reasoning can often stop early without loss. To test this, we conduct early stopping experiments, showing that truncating CoT reasoning still improves performance over not using CoT at all, though a gap remains compared to full reasoning. However, approaches like supervised learning or reinforcement learning designed to shorten CoT chains could leverage our classifier's guidance to identify when early stopping is effective. Our findings provide insights that may support such methods, helping to optimize CoT's efficiency while preserving its benefits.
