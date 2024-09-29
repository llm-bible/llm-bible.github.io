---
layout: publication
title: Tree-Planted Transformers Unidirectional Transformer Language Models with Implicit Syntactic Supervision
authors: Yoshida Ryo, Someya Taiga, Oseki Yohei
conference: "Arxiv"
year: 2024
bibkey: yoshida2024tree
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12691"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Syntactic Language Models (SLMs) can be trained efficiently to reach relatively high performance; however they have trouble with inference efficiency due to the explicit generation of syntactic structures. In this paper we propose a new method dubbed tree-planting instead of explicitly generating syntactic structures we plant trees into attention weights of unidirectional Transformer LMs to implicitly reflect syntactic structures of natural language. Specifically unidirectional Transformer LMs trained with tree-planting will be called Tree-Planted Transformers (TPT) which inherit the training efficiency from SLMs without changing the inference efficiency of their underlying Transformer LMs. Targeted syntactic evaluations on the SyntaxGym benchmark demonstrated that TPTs despite the lack of explicit generation of syntactic structures significantly outperformed not only vanilla Transformer LMs but also various SLMs that generate hundreds of syntactic structures in parallel. This result suggests that TPTs can learn human-like syntactic knowledge as data-efficiently as SLMs while maintaining the modeling space of Transformer LMs unchanged.
