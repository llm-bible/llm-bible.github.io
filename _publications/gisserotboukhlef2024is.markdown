---
layout: publication
title: 'Is Preference Alignment Always The Best Option To Enhance Llm-based Translation? An Empirical Analysis'
authors: Hippolyte Gisserot-boukhlef, Ricardo Rei, Emmanuel Malherbe, Céline Hudelot, Pierre Colombo, Nuno M. Guerreiro
conference: "Arxiv"
year: 2024
bibkey: gisserotboukhlef2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.20059"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
Neural metrics for machine translation (MT) evaluation have become
increasingly prominent due to their superior correlation with human judgments
compared to traditional lexical metrics. Researchers have therefore utilized
neural metrics through quality-informed decoding strategies, achieving better
results than likelihood-based methods. With the rise of Large Language Models
(LLMs), preference-based alignment techniques have gained attention for their
potential to enhance translation quality by optimizing model weights directly
on preferences induced by quality estimators. This study focuses on Contrastive
Preference Optimization (CPO) and conducts extensive experiments to evaluate
the impact of preference-based alignment on translation quality. Our findings
indicate that while CPO consistently outperforms Supervised Fine-Tuning (SFT)
on high-quality data with regard to the alignment metric, it may lead to
instability across downstream evaluation metrics, particularly between neural
and lexical ones. Additionally, we demonstrate that relying solely on the base
model for generating candidate translations achieves performance comparable to
using multiple external systems, while ensuring better consistency across
downstream metrics.
