---
layout: publication
title: 'Gradbias: Unveiling Word Influence On Bias In Text-to-image Generative Models'
authors: Moreno D'incà, Elia Peruzzo, Massimiliano Mancini, Xingqian Xu, Humphrey Shi, Nicu Sebe
conference: "Arxiv"
year: 2024
bibkey: dincà2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16700"}
  - {name: "Code", url: "https://github.com/Moreno98/GradBias"}
tags: ['Responsible AI', 'Tools', 'Ethics and Bias', 'Applications', 'RAG', 'Bias Mitigation', 'Has Code', 'Fairness', 'Prompting']
---
Recent progress in Text-to-Image (T2I) generative models has enabled
high-quality image generation. As performance and accessibility increase, these
models are gaining significant attraction and popularity: ensuring their
fairness and safety is a priority to prevent the dissemination and perpetuation
of biases. However, existing studies in bias detection focus on closed sets of
predefined biases (e.g., gender, ethnicity). In this paper, we propose a
general framework to identify, quantify, and explain biases in an open set
setting, i.e. without requiring a predefined set. This pipeline leverages a
Large Language Model (LLM) to propose biases starting from a set of captions.
Next, these captions are used by the target generative model for generating a
set of images. Finally, Vision Question Answering (VQA) is leveraged for bias
evaluation. We show two variations of this framework: OpenBias and GradBias.
OpenBias detects and quantifies biases, while GradBias determines the
contribution of individual prompt words on biases. OpenBias effectively detects
both well-known and novel biases related to people, objects, and animals and
highly aligns with existing closed-set bias detection methods and human
judgment. GradBias shows that neutral words can significantly influence biases
and it outperforms several baselines, including state-of-the-art foundation
models. Code available here: https://github.com/Moreno98/GradBias.
