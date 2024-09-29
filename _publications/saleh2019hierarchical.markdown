---
layout: publication
title: Hierarchical Reinforcement Learning For Open45;domain Dialog
authors: Saleh Abdelrhman, Jaques Natasha, Ghandeharioun Asma, Shen Judy Hanwen, Picard Rosalind
conference: "Arxiv"
year: 2019
bibkey: saleh2019hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.07547"}
tags: ['Agentic', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Open45;domain dialog generation is a challenging problem; maximum likelihood training can lead to repetitive outputs models have difficulty tracking long45;term conversational goals and training on standard movie or online datasets may lead to the generation of inappropriate biased or offensive text. Reinforcement Learning (RL) is a powerful framework that could potentially address these issues for example by allowing a dialog model to optimize for reducing toxicity and repetitiveness. However previous approaches which apply RL to open45;domain dialog generation do so at the word level making it difficult for the model to learn proper credit assignment for long45;term conversational rewards. In this paper we propose a novel approach to hierarchical reinforcement learning VHRL which uses policy gradients to tune the utterance45;level embedding of a variational sequence model. This hierarchical approach provides greater flexibility for learning long45;term conversational rewards. We use self45;play and RL to optimize for a set of human45;centered conversation metrics and show that our approach provides significant improvements 45;45; in terms of both human evaluation and automatic metrics 45;45; over state45;of45;the45;art dialog models including Transformers.
