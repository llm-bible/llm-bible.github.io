---
layout: publication
title: 'Jailbreaking Large Language Models Through Alignment Vulnerabilities In Out-of-distribution Settings'
authors: Yue Huang, Jingyu Tang, Dongping Chen, Bingda Tang, Yao Wan, Lichao Sun, Philip S. Yu, Xiangliang Zhang
conference: "Arxiv"
year: 2024
bibkey: huang2024jailbreaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13662"}
tags: ['Security', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Prompting', 'Attention Mechanism']
---
Recently, Large Language Models (LLMs) have garnered significant attention
for their exceptional natural language processing capabilities. However,
concerns about their trustworthiness remain unresolved, particularly in
addressing ``jailbreaking'' attacks on aligned LLMs. Previous research
predominantly relies on scenarios involving white-box LLMs or specific, fixed
prompt templates, which are often impractical and lack broad applicability. In
this paper, we introduce a straightforward and novel method called
ObscurePrompt for jailbreaking LLMs, inspired by the observed fragile
alignments in Out-of-Distribution (OOD) data. Specifically, we first formulate
the decision boundary in the jailbreaking process and then explore how obscure
text affects LLM's ethical decision boundary. ObscurePrompt starts with
constructing a base prompt that integrates well-known jailbreaking techniques.
Powerful LLMs are then utilized to obscure the original prompt through
iterative transformations, aiming to bolster the attack's robustness.
Comprehensive experiments show that our approach substantially improves upon
previous methods in terms of attack effectiveness, maintaining efficacy against
two prevalent defense mechanisms.
