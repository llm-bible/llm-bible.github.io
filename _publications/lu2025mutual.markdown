---
layout: publication
title: 'Mutual Reinforcement Of LLM Dialogue Synthesis And Summarization Capabilities For Few-shot Dialogue Summarization'
authors: Yen-ju Lu, Ting-yao Hu, Hema Swetha Koppula, Hadi Pouransari, Jen-hao Rick Chang, Yin Xia, Xiang Kong, Qi Zhu, Simon Wang, Oncel Tuzel, Raviteja Vemulapalli
conference: "Arxiv"
year: 2025
bibkey: lu2025mutual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.17328'}
tags: ['Few-Shot', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'BERT', 'Applications']
---
In this work, we propose Mutual Reinforcing Data Synthesis (MRDS) within LLMs
to improve few-shot dialogue summarization task. Unlike prior methods that
require external knowledge, we mutually reinforce the LLM\'s dialogue synthesis
and summarization capabilities, allowing them to complement each other during
training and enhance overall performances. The dialogue synthesis capability is
enhanced by directed preference optimization with preference scoring from
summarization capability. The summarization capability is enhanced by the
additional high quality dialogue-summary paired data produced by the dialogue
synthesis capability. By leveraging the proposed MRDS mechanism, we elicit the
internal knowledge of LLM in the format of synthetic data, and use it to
augment the few-shot real training dataset. Empirical results demonstrate that
our method improves dialogue summarization, achieving a 1.5% increase in ROUGE
scores and a 0.3% improvement in BERT scores in few-shot settings. Furthermore,
our method attains the highest average scores in human evaluations, surpassing
both the pre-trained models and the baselines fine-tuned solely for
summarization tasks.
