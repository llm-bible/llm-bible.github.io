---
layout: publication
title: 'Optimizing Humor Generation In Large Language Models: Temperature Configurations And Architectural Trade-offs'
authors: Evgenii Evstafev
conference: "Arxiv"
year: 2025
bibkey: evstafev2025optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02858"}
tags: ['Efficiency and Optimization', 'Applications', 'Language Modeling', 'Model Architecture', 'Prompting']
---
Large language models (LLMs) demonstrate increasing capabilities in creative
text generation, yet systematic evaluations of their humor production remain
underexplored. This study presents a comprehensive analysis of 13
state-of-the-art LLMs across five architectural families, evaluating their
performance in generating technically relevant humor for software developers.
Through a full factorial design testing 715 unique configurations of
temperature settings and prompt variations, we assess model outputs using five
weighted criteria: humor quality, domain relevance, concept originality, tone
precision, and delivery efficiency. Our methodology employs rigorous
statistical analysis including ANOVA, correlation studies, and quadratic
regression to identify optimal configurations and architectural influences.
Results reveal significant performance variations across models, with certain
architectures achieving 21.8% superiority over baseline systems. Temperature
sensitivity analysis demonstrates that 73% of models achieve peak performance
at lower stochasticity settings (<= 0.5), though optimal ranges vary
substantially by architecture. We identify distinct model clusters: compact
high-performers maintaining efficiency-quality balance versus verbose
specialists requiring longer outputs for marginal gains. Statistical validation
confirms model architecture explains 38.7% of performance variance, with
significant correlations between humor quality and concept originality. The
study establishes practical guidelines for model selection and configuration,
demonstrating how temperature adjustments and architectural considerations
impact humor generation effectiveness. These findings advance understanding of
LLM capabilities in creative technical writing and provide empirically
validated configuration strategies for developers implementing humor-generation
systems.
