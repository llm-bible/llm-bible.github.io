---
layout: publication
title: 'CLAIR-A: Leveraging Large Language Models To Judge Audio Captions'
authors: Tsung-han Wu, Joseph E. Gonzalez, Trevor Darrell, David M. Chan
conference: "Arxiv"
year: 2024
bibkey: wu2024clair
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12962"}
  - {name: "Code", url: "https://github.com/DavidMChan/clair-a"}
tags: ['Ethics and Bias', 'Interpretability and Explainability', 'RAG', 'Interpretability', 'Has Code']
---
The Automated Audio Captioning (AAC) task asks models to generate natural
language descriptions of an audio input. Evaluating these machine-generated
audio captions is a complex task that requires considering diverse factors,
among them, auditory scene understanding, sound-object inference, temporal
coherence, and the environmental context of the scene. While current methods
focus on specific aspects, they often fail to provide an overall score that
aligns well with human judgment. In this work, we propose CLAIR-A, a simple and
flexible method that leverages the zero-shot capabilities of large language
models (LLMs) to evaluate candidate audio captions by directly asking LLMs for
a semantic distance score. In our evaluations, CLAIR-A better predicts human
judgements of quality compared to traditional metrics, with a 5.8% relative
accuracy improvement compared to the domain-specific FENSE metric and up to 11%
over the best general-purpose measure on the Clotho-Eval dataset. Moreover,
CLAIR-A offers more transparency by allowing the language model to explain the
reasoning behind its scores, with these explanations rated up to 30% better by
human evaluators than those provided by baseline methods. CLAIR-A is made
publicly available at https://github.com/DavidMChan/clair-a.
