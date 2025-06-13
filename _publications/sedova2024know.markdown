---
layout: publication
title: 'To Know Or Not To Know? Analyzing Self-consistency Of Large Language Models Under Ambiguity'
authors: Anastasiia Sedova, Robert Litschko, Diego Frassinelli, Benjamin Roth, Barbara Plank
conference: "Arxiv"
year: 2024
bibkey: sedova2024know
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.17125'}
tags: ['Pre-Training', 'RAG', 'Training Techniques', 'Prompting', 'Ethics and Bias']
---
One of the major aspects contributing to the striking performance of large
language models (LLMs) is the vast amount of factual knowledge accumulated
during pre-training. Yet, many LLMs suffer from self-inconsistency, which
raises doubts about their trustworthiness and reliability. This paper focuses
on entity type ambiguity, analyzing the proficiency and consistency of
state-of-the-art LLMs in applying factual knowledge when prompted with
ambiguous entities. To do so, we propose an evaluation protocol that
disentangles knowing from applying knowledge, and test state-of-the-art LLMs on
49 ambiguous entities. Our experiments reveal that LLMs struggle with choosing
the correct entity reading, achieving an average accuracy of only 85%, and as
low as 75% with underspecified prompts. The results also reveal systematic
discrepancies in LLM behavior, showing that while the models may possess
knowledge, they struggle to apply it consistently, exhibit biases toward
preferred readings, and display self-inconsistencies. This highlights the need
to address entity ambiguity in the future for more trustworthy LLMs.
