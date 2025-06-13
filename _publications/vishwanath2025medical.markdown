---
layout: publication
title: 'Medical Large Language Models Are Easily Distracted'
authors: Krithik Vishwanath, Anton Alyakin, Daniel Alexander Alber, Jin Vivian Lee, Douglas Kondziolka, Eric Karl Oermann
conference: "Arxiv"
year: 2025
bibkey: vishwanath2025medical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01201'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) have the potential to transform medicine, but
real-world clinical scenarios contain extraneous information that can hinder
performance. The rise of assistive technologies like ambient dictation, which
automatically generates draft notes from live patient encounters, has the
potential to introduce additional noise making it crucial to assess the ability
of LLM's to filter relevant data. To investigate this, we developed
MedDistractQA, a benchmark using USMLE-style questions embedded with simulated
real-world distractions. Our findings show that distracting statements
(polysemous words with clinical meanings used in a non-clinical context or
references to unrelated health conditions) can reduce LLM accuracy by up to
17.9%. Commonly proposed solutions to improve model performance such as
retrieval-augmented generation (RAG) and medical fine-tuning did not change
this effect and in some cases introduced their own confounders and further
degraded performance. Our findings suggest that LLMs natively lack the logical
mechanisms necessary to distinguish relevant from irrelevant clinical
information, posing challenges for real-world applications. MedDistractQA and
our results highlights the need for robust mitigation strategies to enhance LLM
resilience to extraneous information.
