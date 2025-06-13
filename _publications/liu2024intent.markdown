---
layout: publication
title: 'Intent-aware Dialogue Generation And Multi-task Contrastive Learning For Multi-turn Intent Classification'
authors: Junhua Liu, Yong Keat Tan, Bin Fu, Kwan Hui Lim
conference: "Arxiv"
year: 2024
bibkey: liu2024intent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14252"}
tags: ['Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Generating large-scale, domain-specific, multilingual multi-turn dialogue
datasets remains a significant hurdle for training effective Multi-Turn Intent
Classification models in chatbot systems. In this paper, we introduce
Chain-of-Intent, a novel mechanism that combines Hidden Markov Models with
Large Language Models (LLMs) to generate contextually aware, intent-driven
conversations through self-play. By extracting domain-specific knowledge from
e-commerce chat logs, we estimate conversation turns and intent transitions,
which guide the generation of coherent dialogues. Leveraging LLMs to enhance
emission probabilities, our approach produces natural and contextually
consistent questions and answers. We also propose MINT-CL, a framework for
multi-turn intent classification using multi-task contrastive learning,
improving classification accuracy without the need for extensive annotated
data. Evaluations show that our methods outperform baselines in dialogue
quality and intent classification accuracy, especially in multilingual
settings, while significantly reducing data generation efforts. Furthermore, we
release MINT-E, a multilingual, intent-aware multi-turn e-commerce dialogue
corpus to support future research in this area.
