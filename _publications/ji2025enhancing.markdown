---
layout: publication
title: 'Enhancing Persona Consistency For Llms'' Role-playing Using Persona-aware Contrastive Learning'
authors: Ke Ji, Yixin Lian, Linxu Li, Jingsheng Gao, Weiyuan Li, Bin Dai
conference: "Arxiv"
year: 2025
bibkey: ji2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17662"}
tags: ['Responsible AI', 'Agentic', 'GPT', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
In recent years, large language models (LLMs) have achieved breakthrough
progress in many dialogue generation tasks. However, their lack of emotion and
fine-grained role awareness limits the model's ability to provide personalized
and diverse interactions further. Current methods face high costs in collecting
high-quality annotated data for scenarios such as role-playing, and traditional
human alignment methods are difficult to deploy due to the inherent diversity
of model behavior in role-playing scenarios. Inspired by the alignment of
models for safety behaviors through RLHF (Reinforcement Learning from Human
Feedback), in this paper, we revisit model role-playing behavior from the
perspective of persona alignment and propose a novel annotation-free framework
named \textbf\{\underline\{P\}\}ersona-Aware \textbf\{\underline\{C\}\}ontrastive
\textbf\{\underline\{L\}\}earning (PCL) to align LLMs' behavior during
role-playing, enhancing the model's role consistency. Specifically, we first
design a role chain method to encourage the model to self-question based on the
role characteristics and dialogue context to adjust personality consistency.
Then, we further enhance the model's role-playing strategy through iterative
contrastive learning between the use of role characteristics and not.
Experiments on both black-box and white-box LLMs show that LLMs equipped with
PCL significantly outperform vanilla LLMs under automatic evaluation methods
(CharEval \& GPT-4) and human expert evaluation.
