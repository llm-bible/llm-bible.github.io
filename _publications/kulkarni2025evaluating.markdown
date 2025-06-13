---
layout: publication
title: 'Evaluating Evaluation Metrics -- The Mirage Of Hallucination Detection'
authors: Atharva Kulkarni, Yuan Zhang, Joel Ruben Antony Moniz, Xiou Ge, Bo-hsiang Tseng, Dhivya Piraviperumal, Swabha Swayamdipta, Hong Yu
conference: "Arxiv"
year: 2025
bibkey: kulkarni2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18114"}
tags: ['GPT', 'RAG', 'TACL', 'Model Architecture', 'Reinforcement Learning', 'ACL', 'Security']
---
Hallucinations pose a significant obstacle to the reliability and widespread
adoption of language models, yet their accurate measurement remains a
persistent challenge. While many task- and domain-specific metrics have been
proposed to assess faithfulness and factuality concerns, the robustness and
generalization of these metrics are still untested. In this paper, we conduct a
large-scale empirical evaluation of 6 diverse sets of hallucination detection
metrics across 4 datasets, 37 language models from 5 families, and 5 decoding
methods. Our extensive investigation reveals concerning gaps in current
hallucination evaluation: metrics often fail to align with human judgments,
take an overtly myopic view of the problem, and show inconsistent gains with
parameter scaling. Encouragingly, LLM-based evaluation, particularly with
GPT-4, yields the best overall results, and mode-seeking decoding methods seem
to reduce hallucinations, especially in knowledge-grounded settings. These
findings underscore the need for more robust metrics to understand and quantify
hallucinations, and better strategies to mitigate them.
