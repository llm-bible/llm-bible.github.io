---
layout: publication
title: 'Landscape Of Thoughts: Visualizing The Reasoning Process Of Large Language Models'
authors: Zhanke Zhou, Zhaocheng Zhu, Xuan Li, Mikhail Galkin, Xiao Feng, Sanmi Koyejo, Jian Tang, Bo Han
conference: "Arxiv"
year: 2025
bibkey: zhou2025landscape
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22165"}
  - {name: "Code", url: "https://github.com/tmlr-group/landscape-of-thoughts"}
tags: ['Responsible AI', 'Applications', 'Has Code', 'Reinforcement Learning']
---
Numerous applications of large language models (LLMs) rely on their ability
to perform step-by-step reasoning. However, the reasoning behavior of LLMs
remains poorly understood, posing challenges to research, development, and
safety. To address this gap, we introduce landscape of thoughts-the first
visualization tool for users to inspect the reasoning paths of chain-of-thought
and its derivatives on any multi-choice dataset. Specifically, we represent the
states in a reasoning path as feature vectors that quantify their distances to
all answer choices. These features are then visualized in two-dimensional plots
using t-SNE. Qualitative and quantitative analysis with the landscape of
thoughts effectively distinguishes between strong and weak models, correct and
incorrect answers, as well as different reasoning tasks. It also uncovers
undesirable reasoning patterns, such as low consistency and high uncertainty.
Additionally, users can adapt our tool to a model that predicts the property
they observe. We showcase this advantage by adapting our tool to a lightweight
verifier that evaluates the correctness of reasoning paths. The code is
publicly available at: https://github.com/tmlr-group/landscape-of-thoughts.
