---
layout: publication
title: 'Enhancing Large Language Models Through Neuro-symbolic Integration And Ontological Reasoning'
authors: Ruslan Idelfonso Magana Vsevolodovna, Marco Monti
conference: "Arxiv"
year: 2025
bibkey: vsevolodovna2025enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.07640'}
tags: ['Uncategorized']
---
Large Language Models (LLMs) demonstrate impressive capabilities in natural
language processing but suffer from inaccuracies and logical inconsistencies
known as hallucinations. This compromises their reliability, especially in
domains requiring factual accuracy. We propose a neuro-symbolic approach
integrating symbolic ontological reasoning and machine learning methods to
enhance the consistency and reliability of LLM outputs. Our workflow utilizes
OWL ontologies, a symbolic reasoner (e.g., HermiT) for consistency checking,
and a lightweight machine learning model (logistic regression) for mapping
natural language statements into logical forms compatible with the ontology.
When inconsistencies between LLM outputs and the ontology are detected, the
system generates explanatory feedback to guide the LLM towards a corrected,
logically coherent response in an iterative refinement loop. We present a
working Python prototype demonstrating this pipeline. Experimental results in a
defined domain suggest significant improvements in semantic coherence and
factual accuracy of LLM outputs, showcasing the potential of combining LLM
fluency with the rigor of formal semantics.
