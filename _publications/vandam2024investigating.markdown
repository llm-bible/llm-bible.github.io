---
layout: publication
title: Investigating The Performance Of Language Models For Completing Code In Functional Programming Languages A Haskell Case Study
authors: Van Dam Tim, Van Der Heijden Frank, De Bekker Philippe, Nieuwschepen Berend, Otten Marc, Izadi Maliheh
conference: "Arxiv"
year: 2024
bibkey: vandam2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15185"}
  - {name: "Code", url: "https://github.com/AISE-TUDelft/HaskellCCEval)"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Language model-based code completion models have quickly grown in use helping thousands of developers write code in many different programming languages. However research on code completion models typically focuses on imperative languages such as Python and JavaScript which results in a lack of representation for functional programming languages. Consequently these models often perform poorly on functional languages such as Haskell. To investigate whether this can be alleviated we evaluate the performance of two language models for code CodeGPT and UniXcoder on the functional programming language Haskell. We fine-tune and evaluate the models on Haskell functions sourced from a publicly accessible Haskell dataset on HuggingFace. Additionally we manually evaluate the models using our novel translated HumanEval dataset. Our automatic evaluation shows that knowledge of imperative programming languages in the pre-training of LLMs may not transfer well to functional languages but that code completion on functional languages is feasible. Consequently this shows the need for more high-quality Haskell datasets. A manual evaluation on HumanEval-Haskell indicates CodeGPT frequently generates empty predictions and extra comments while UniXcoder more often produces incomplete or incorrect predictions. Finally we release HumanEval-Haskell along with the fine-tuned models and all code required to reproduce our experiments on GitHub (https://github.com/AISE-TUDelft/HaskellCCEval).
