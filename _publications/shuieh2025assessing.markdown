---
layout: publication
title: 'Assessing Robustness To Spurious Correlations In Post-training Language Models'
authors: Julia Shuieh, Prasann Singhal, Apaar Shanker, John Heyer, George Pu, Samuel Denton
conference: "Arxiv"
year: 2025
bibkey: shuieh2025assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05704"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Ethics and Bias', 'Applications', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Supervised and preference-based fine-tuning techniques have become popular for aligning large language models (LLMs) with user intent and correctness criteria. However, real-world training data often exhibits spurious correlations -- arising from biases, dataset artifacts, or other "shortcut" features -- that can compromise a model's performance or generalization. In this paper, we systematically evaluate three post-training algorithms -- Supervised Fine-Tuning (SFT), Direct Preference Optimization (DPO), and KTO (Kahneman-Tversky Optimization) -- across a diverse set of synthetic tasks and spuriousness conditions. Our tasks span mathematical reasoning, constrained instruction-following, and document-grounded question answering. We vary the degree of spurious correlation (10% vs. 90%) and investigate two forms of artifacts: "Feature Ambiguity" and "Distributional Narrowness." Our results show that the models often but not always degrade under higher spuriousness. The preference-based methods (DPO/KTO) can demonstrate relative robustness in mathematical reasoning tasks. By contrast, SFT maintains stronger performance in complex, context-intensive tasks. These findings highlight that no single post-training strategy universally outperforms in all scenarios; the best choice depends on the type of target task and the nature of spurious correlations.
