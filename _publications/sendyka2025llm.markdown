---
layout: publication
title: 'LLM Performance For Code Generation On Noisy Tasks'
authors: Radzim Sendyka, Christian Cabrera, Andrei Paleyes, Diana Robinson, Neil Lawrence
conference: "Arxiv"
year: 2025
bibkey: sendyka2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23598"}
tags: ['Interpretability and Explainability', 'Applications', 'Training Techniques', 'Responsible AI']
---
This paper investigates the ability of large language models (LLMs) to recognise and solve tasks which have been obfuscated beyond recognition. Focusing on competitive programming and benchmark tasks (LeetCode and MATH), we compare performance across multiple models and obfuscation methods, such as noise and redaction. We demonstrate that all evaluated LLMs can solve tasks obfuscated to a level where the text would be unintelligible to human readers, and does not contain key pieces of instruction or context. We introduce the concept of eager pattern matching to describe this behaviour, which is not observed in tasks published after the models' knowledge cutoff date, indicating strong memorisation or overfitting to training data, rather than legitimate reasoning about the presented problem. We report empirical evidence of distinct performance decay patterns between contaminated and unseen datasets. We discuss the implications for benchmarking and evaluations of model behaviour, arguing for caution when designing experiments using standard datasets. We also propose measuring the decay of performance under obfuscation as a possible strategy for detecting dataset contamination and highlighting potential safety risks and interpretability issues for automated software systems.
