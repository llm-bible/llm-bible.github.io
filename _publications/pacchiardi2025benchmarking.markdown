---
layout: publication
title: 'Predictaboard: Benchmarking LLM Score Predictability'
authors: Lorenzo Pacchiardi, Konstantinos Voudouris, Ben Slater, Fernando Martínez-plumed, José Hernández-orallo, Lexin Zhou, Wout Schellaert
conference: "Arxiv"
year: 2025
bibkey: pacchiardi2025benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14445"}
  - {name: "Code", url: "https://github.com/Kinds-of-Intelligence-CFI/PredictaBoard"}
tags: ['Prompting', 'RAG', 'Has Code', 'Tools']
---
Despite possessing impressive skills, Large Language Models (LLMs) often fail
unpredictably, demonstrating inconsistent success in even basic common sense
reasoning tasks. This unpredictability poses a significant challenge to
ensuring their safe deployment, as identifying and operating within a reliable
"safe zone" is essential for mitigating risks. To address this, we present
PredictaBoard, a novel collaborative benchmarking framework designed to
evaluate the ability of score predictors (referred to as assessors) to
anticipate LLM errors on specific task instances (i.e., prompts) from existing
datasets. PredictaBoard evaluates pairs of LLMs and assessors by considering
the rejection rate at different tolerance errors. As such, PredictaBoard
stimulates research into developing better assessors and making LLMs more
predictable, not only with a higher average performance. We conduct
illustrative experiments using baseline assessors and state-of-the-art LLMs.
PredictaBoard highlights the critical need to evaluate predictability alongside
performance, paving the way for safer AI systems where errors are not only
minimised but also anticipated and effectively mitigated. Code for our
benchmark can be found at
https://github.com/Kinds-of-Intelligence-CFI/PredictaBoard
