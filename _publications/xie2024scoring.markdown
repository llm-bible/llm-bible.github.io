---
layout: publication
title: 'Scoring With Large Language Models: A Study On Measuring Empathy Of Responses In Dialogues'
authors: Henry J. Xie, Jinghan Zhang, Xinhao Zhang, Kunpeng Liu
conference: "Arxiv"
year: 2024
bibkey: xie2024scoring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20264"}
tags: ['Tools']
---
In recent years, Large Language Models (LLMs) have become increasingly more
powerful in their ability to complete complex tasks. One such task in which
LLMs are often employed is scoring, i.e., assigning a numerical value from a
certain scale to a subject. In this paper, we strive to understand how LLMs
score, specifically in the context of empathy scoring. We develop a novel and
comprehensive framework for investigating how effective LLMs are at measuring
and scoring empathy of responses in dialogues, and what methods can be employed
to deepen our understanding of LLM scoring. Our strategy is to approximate the
performance of state-of-the-art and fine-tuned LLMs with explicit and
explainable features. We train classifiers using various features of dialogues
including embeddings, the Motivational Interviewing Treatment Integrity (MITI)
Code, a set of explicit subfactors of empathy as proposed by LLMs, and a
combination of the MITI Code and the explicit subfactors. Our results show that
when only using embeddings, it is possible to achieve performance close to that
of generic LLMs, and when utilizing the MITI Code and explicit subfactors
scored by an LLM, the trained classifiers can closely match the performance of
fine-tuned LLMs. We employ feature selection methods to derive the most crucial
features in the process of empathy scoring. Our work provides a new perspective
toward understanding LLM empathy scoring and helps the LLM community explore
the potential of LLM scoring in social science studies.
