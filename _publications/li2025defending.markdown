---
layout: publication
title: 'DETAM: Defending Llms Against Jailbreak Attacks Via Targeted Attention Modification'
authors: Yu Li, Han Jiang, Zhihua Wei
conference: "Arxiv"
year: 2025
bibkey: li2025defending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13562"}
tags: ['Fine-Tuning', 'Responsible AI', 'Model Architecture', 'Security', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
With the widespread adoption of Large Language Models (LLMs), jailbreak
attacks have become an increasingly pressing safety concern. While
safety-aligned LLMs can effectively defend against normal harmful queries, they
remain vulnerable to such attacks. Existing defense methods primarily rely on
fine-tuning or input modification, which often suffer from limited
generalization and reduced utility. To address this, we introduce DETAM, a
finetuning-free defense approach that improves the defensive capabilities
against jailbreak attacks of LLMs via targeted attention modification.
Specifically, we analyze the differences in attention scores between successful
and unsuccessful defenses to identify the attention heads sensitive to
jailbreak attacks. During inference, we reallocate attention to emphasize the
user's core intention, minimizing interference from attack tokens. Our
experimental results demonstrate that DETAM outperforms various baselines in
jailbreak defense and exhibits robust generalization across different attacks
and models, maintaining its effectiveness even on in-the-wild jailbreak data.
Furthermore, in evaluating the model's utility, we incorporated over-defense
datasets, which further validate the superior performance of our approach. The
code will be released immediately upon acceptance.
