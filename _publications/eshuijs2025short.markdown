---
layout: publication
title: 'Short-circuiting Shortcuts: Mechanistic Investigation Of Shortcuts In Text Classification'
authors: Leon Eshuijs, Shihan Wang, Antske Fokkens
conference: "Arxiv"
year: 2025
bibkey: eshuijs2025short
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.06032"}
tags: ['Interpretability and Explainability', 'Model Architecture', 'Attention Mechanism', 'Reinforcement Learning']
---
Reliance on spurious correlations (shortcuts) has been shown to underlie many of the successes of language models. Previous work focused on identifying the input elements that impact prediction. We investigate how shortcuts are actually processed within the model's decision-making mechanism. We use actor names in movie reviews as controllable shortcuts with known impact on the outcome. We use mechanistic interpretability methods and identify specific attention heads that focus on shortcuts. These heads gear the model towards a label before processing the complete input, effectively making premature decisions that bypass contextual analysis. Based on these findings, we introduce Head-based Token Attribution (HTA), which traces intermediate decisions back to input tokens. We show that HTA is effective in detecting shortcuts in LLMs and enables targeted mitigation by selectively deactivating shortcut-related attention heads.
