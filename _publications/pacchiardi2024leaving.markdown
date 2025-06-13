---
layout: publication
title: 'Leaving The Barn Door Open For Clever Hans: Simple Features Predict LLM Benchmark Answers'
authors: Lorenzo Pacchiardi, Marko Tesic, Lucy G. Cheke, José Hernández-orallo
conference: "Arxiv"
year: 2024
bibkey: pacchiardi2024leaving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.11672'}
tags: ['Uncategorized']
---
The integrity of AI benchmarks is fundamental to accurately assess the
capabilities of AI systems. The internal validity of these benchmarks - i.e.,
making sure they are free from confounding factors - is crucial for ensuring
that they are measuring what they are designed to measure. In this paper, we
explore a key issue related to internal validity: the possibility that AI
systems can solve benchmarks in unintended ways, bypassing the capability being
tested. This phenomenon, widely known in human and animal experiments, is often
referred to as the 'Clever Hans' effect, where tasks are solved using spurious
cues, often involving much simpler processes than those putatively assessed.
Previous research suggests that language models can exhibit this behaviour as
well. In several older Natural Language Processing (NLP) benchmarks, individual
\\(n\\)-grams like "not" have been found to be highly predictive of the correct
labels, and supervised NLP models have been shown to exploit these patterns. In
this work, we investigate the extent to which simple \\(n\\)-grams extracted from
benchmark instances can be combined to predict labels in modern multiple-choice
benchmarks designed for LLMs, and whether LLMs might be using such \\(n\\)-gram
patterns to solve these benchmarks. We show how simple classifiers trained on
these \\(n\\)-grams can achieve high scores on several benchmarks, despite lacking
the capabilities being tested. Additionally, we provide evidence that modern
LLMs might be using these superficial patterns to solve benchmarks. This
suggests that the internal validity of these benchmarks may be compromised and
caution should be exercised when interpreting LLM performance results on them.
