---
layout: publication
title: Predicting Vs. Acting: A Trade-off Between World Modeling & Agent Modeling
authors: Li Margaret, Shi Weijia, Pagnoni Artidoro, West Peter, Holtzman Ari
conference: "Arxiv"
year: 2024
bibkey: li2024predicting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02446"}
tags: ['Agentic', 'Applications', 'Interpretability And Explainability', 'Language Modeling', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
RLHF-aligned LMs have shown unprecedented ability on both benchmarks and long-form text generation yet they struggle with one foundational task next-token prediction. As RLHF models become agent models aimed at interacting with humans they seem to lose their world modeling -- the ability to predict what comes next in arbitrary documents which is the foundational training objective of the Base LMs that RLHF adapts. Besides empirically demonstrating this trade-off we propose a potential explanation to perform coherent long-form generation RLHF models restrict randomness via implicit blueprints. In particular RLHF models concentrate probability on sets of anchor spans that co-occur across multiple generations for the same prompt serving as textual scaffolding but also limiting a models ability to generate documents that do not include these spans. We study this trade-off on the most effective current agent models those aligned with RLHF while exploring why this may remain a fundamental trade-off between models that act and those that predict even as alignment techniques improve.
