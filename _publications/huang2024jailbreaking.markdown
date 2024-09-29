---
layout: publication
title: Obscureprompt: Jailbreaking Large Language Models Via Obscure Input
authors: Huang Yue, Tang Jingyu, Chen Dongping, Tang Bingda, Wan Yao, Sun Lichao, Zhang Xiangliang
conference: "Arxiv"
year: 2024
bibkey: huang2024jailbreaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13662"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security']
---
Recently Large Language Models (LLMs) have garnered significant attention for their exceptional natural language processing capabilities. However concerns about their trustworthiness remain unresolved particularly in addressing jailbreaking attacks on aligned LLMs. Previous research predominantly relies on scenarios with white-box LLMs or specific and fixed prompt templates which are often impractical and lack broad applicability. In this paper we introduce a straightforward and novel method named ObscurePrompt for jailbreaking LLMs inspired by the observed fragile alignments in Out-of-Distribution (OOD) data. Specifically we first formulate the decision boundary in the jailbreaking process and then explore how obscure text affects LLMs ethical decision boundary. ObscurePrompt starts with constructing a base prompt that integrates well-known jailbreaking techniques. Powerful LLMs are then utilized to obscure the original prompt through iterative transformations aiming to bolster the attacks robustness. Comprehensive experiments show that our approach substantially improves upon previous methods in terms of attack effectiveness maintaining efficacy against two prevalent defense mechanisms. We believe that our work can offer fresh insights for future research on enhancing LLM alignment.
