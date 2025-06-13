---
layout: publication
title: 'Multi-domain Explainability Of Preferences'
authors: Nitay Calderon, Liat Ein-dor, Roi Reichart
conference: "Arxiv"
year: 2025
bibkey: calderon2025multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20088'}
tags: ['Reinforcement Learning', 'Prompting', 'Interpretability', 'Interpretability and Explainability']
---
Preference mechanisms, such as human preference, LLM-as-a-Judge (LaaJ), and reward models, are central to aligning and evaluating large language models (LLMs). Yet, the underlying concepts that drive these preferences remain poorly understood. In this work, we propose a fully automated method for generating local and global concept-based explanations of preferences across multiple domains. Our method utilizes an LLM to identify concepts that distinguish between chosen and rejected responses, and to represent them with concept-based vectors. To model the relationships between concepts and preferences, we propose a white-box Hierarchical Multi-Domain Regression model that captures both domain-general and domain-specific effects. To evaluate our method, we curate a dataset spanning eight challenging and diverse domains and explain twelve mechanisms. Our method achieves strong preference prediction performance, outperforming baselines while also being explainable. Additionally, we assess explanations in two application-driven settings. First, guiding LLM outputs with concepts from LaaJ explanations yields responses that those judges consistently prefer. Second, prompting LaaJs with concepts explaining humans improves their preference predictions. Together, our work establishes a new paradigm for explainability in the era of LLMs.
