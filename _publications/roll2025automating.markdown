---
layout: publication
title: 'Polyprompt: Automating Knowledge Extraction From Multilingual Language Models With Dynamic Prompt Generation'
authors: Nathan Roll
conference: "Arxiv"
year: 2025
bibkey: roll2025automating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19756"}
tags: ['Prompting', 'Tools']
---
Large language models (LLMs) showcase increasingly impressive English benchmark scores, however their performance profiles remain inconsistent across multilingual settings. To address this gap, we introduce PolyPrompt, a novel, parameter-efficient framework for enhancing the multilingual capabilities of LLMs. Our method learns a set of trigger tokens for each language through a gradient-based search, identifying the input query's language and selecting the corresponding trigger tokens which are prepended to the prompt during inference. We perform experiments on two ~1 billion parameter models, with evaluations on the global MMLU benchmark across fifteen typologically and resource diverse languages, demonstrating accuracy gains of 3.7%-19.9% compared to naive and translation-pipeline baselines.
