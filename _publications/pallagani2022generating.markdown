---
layout: publication
title: 'Plansformer: Generating Symbolic Plans Using Transformers'
authors: Vishal Pallagani, Bharath Muppasani, Keerthiram Murugesan, Francesca Rossi, Lior Horesh, Biplav Srivastava, Francesco Fabiano, Andrea Loreggia
conference: "Arxiv"
year: 2022
bibkey: pallagani2022generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.08681"}
tags: ['Agentic', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Pretraining Methods', 'BERT', 'Transformer', 'Fine-Tuning', 'Applications']
---
Large Language Models (LLMs) have been the subject of active research,
significantly advancing the field of Natural Language Processing (NLP). From
BERT to BLOOM, LLMs have surpassed state-of-the-art results in various natural
language tasks such as question answering, summarization, and text generation.
Many ongoing efforts focus on understanding LLMs' capabilities, including their
knowledge of the world, syntax, and semantics. However, extending the textual
prowess of LLMs to symbolic reasoning has been slow and predominantly focused
on tackling problems related to the mathematical field. In this paper, we
explore the use of LLMs for automated planning - a branch of AI concerned with
the realization of action sequences (plans) to achieve a goal, typically
executed by intelligent agents, autonomous robots, and unmanned vehicles. We
introduce Plansformer; an LLM fine-tuned on planning problems and capable of
generating plans with favorable behavior in terms of correctness and length
with reduced knowledge-engineering efforts. We also demonstrate the
adaptability of Plansformer in solving different planning domains with varying
complexities, owing to the transfer learning abilities of LLMs. For one
configuration of Plansformer, we achieve ~97% valid plans, out of which ~95%
are optimal for Towers of Hanoi - a puzzle-solving domain.
