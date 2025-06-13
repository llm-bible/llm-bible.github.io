---
layout: publication
title: 'Self-correction Is Not An Innate Capability In Large Language Models: A Case Study Of Moral Self-correction'
authors: Guangliang Liu, Zimo Qi, Xitong Zhang, Lu Cheng, Kristen Marie Johnson
conference: "Arxiv"
year: 2024
bibkey: liu2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.20513"}
tags: ['RAG', 'Model Architecture', 'Attention Mechanism', 'Tools']
---
Though there has been intensive attention to the self-correction capability
of Large Language Models (LLMs), conclusions regarding its effectiveness remain
varied. In this paper, we investigate a fundamental question: is moral
self-correction an innate capability in LLMs? To explore this, we conduct (1) a
mechanistic analysis of how key components of self-correction, such as
Chain-of-Thought (CoT) reasoning and external feedback, interact to enable
moral self-correction; and (2) a behavioral analysis of LLMs' ability to
distinguish between desired and undesired outputs, introducing a
self-distinguish framework. Our mechanistic analysis reveals that LLMs struggle
to effectively leverage helpful feedback, and conflicts can arise between
feedback and CoT reasoning. These limitations suggest that LLMs fail to
identify useful contextual information, instead prioritizing their own internal
knowledge. Additionally, our behavioral analysis indicates that LLMs struggle
to differentiate among their own outputs. Based on these empirical findings
across two analytical dimensions, mechanism and behavior, we argue that moral
self-correction is not an innate capability of LLMs.
