---
layout: publication
title: 'TRATES: Trait-specific Rubric-assisted Cross-prompt Essay Scoring'
authors: Sohaila Eltanbouly, Salam Albatarni, Tamer Elsayed
conference: "Arxiv"
year: 2025
bibkey: eltanbouly2025trait
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14577"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Attention Mechanism']
---
Research on holistic Automated Essay Scoring (AES) is long-dated; yet, there is a notable lack of attention for assessing essays according to individual traits. In this work, we propose TRATES, a novel trait-specific and rubric-based cross-prompt AES framework that is generic yet specific to the underlying trait. The framework leverages a Large Language Model (LLM) that utilizes the trait grading rubrics to generate trait-specific features (represented by assessment questions), then assesses those features given an essay. The trait-specific features are eventually combined with generic writing-quality and prompt-specific features to train a simple classical regression model that predicts trait scores of essays from an unseen prompt. Experiments show that TRATES achieves a new state-of-the-art performance across all traits on a widely-used dataset, with the generated LLM-based features being the most significant.
