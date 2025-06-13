---
layout: publication
title: 'Reasoning Can Hurt The Inductive Abilities Of Large Language Models'
authors: Haibo Jin, Peiyan Zhang, Man Luo, Haohan Wang
conference: "Arxiv"
year: 2025
bibkey: jin2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24225"}
tags: ['Prompting', 'Training Techniques', 'Applications', 'Tools']
---
Large Language Models (LLMs) have shown remarkable progress across domains, yet their ability to perform inductive reasoning - inferring latent rules from sparse examples - remains limited. It is often assumed that chain-of-thought (CoT) prompting, as used in Large Reasoning Models (LRMs), enhances such reasoning. We investigate this assumption with creating four controlled, diagnostic game-based tasks - chess, Texas Hold'em, dice games, and blackjack - with hidden human-defined rules. We find that CoT reasoning can degrade inductive performance, with LRMs often underperforming their non-reasoning counterparts.
  To explain this, we present a theoretical framework that reveals how reasoning steps can amplify error through three failure modes: incorrect sub-task decomposition, incorrect sub-task solving, and incorrect final answer summarization. Based on our theoretical and empirical analysis, we introduce structured interventions that adapt CoT generation according to our identified failure types. These interventions improve inductive accuracy without retraining. Our findings suggest that effective (CoT) reasoning depends not only on taking more steps but also on ensuring those steps are well-structured.
