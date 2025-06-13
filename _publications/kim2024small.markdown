---
layout: publication
title: 'Small Language Models Are Equation Reasoners'
authors: Bumjun Kim, Kunha Lee, Juyeon Kim, Sangam Lee
conference: "Arxiv"
year: 2024
bibkey: kim2024small
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.12393'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Distillation']
---
Chain-of-Thought (CoT) reasoning has enabled Large Language Model (LLM) to
achieve remarkable performance in various NLP tasks, including arithmetic
problem-solving. However, this success does not generalize to small language
model (sLM) like T5, due to their limited capacity and absence of emergent
abilities associated with larger models. Recent works to enhance sLM through
knowledge distillation have yielded some improvements but still face
significant limitations, particularly high ambiguity from the variability in
natural language expressions and substantial computational costs. In this
paper, we investigate why sLM perform poorly on arithmetic reasoning tasks and
hypothesize that natural language format variability introduces high ambiguity
for these smaller models. Based on this hypothesis, we conduct experiments with
equation-only format, which is a reasoning format that unifies arithmetic
reasoning previously expressed in natural language formats into mathematical
equations. Experiment results demonstrate that equation-only format effectively
boosts the arithmetic reasoning abilities of sLM, especially in very small
models like T5-Tiny.
