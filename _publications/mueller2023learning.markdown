---
layout: publication
title: In45;context Learning Generalizes But Not Always Robustly The Case Of Syntax
authors: Mueller Aaron, Webson Albert, Petty Jackson, Linzen Tal
conference: "Arxiv"
year: 2023
bibkey: mueller2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07811"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
In45;context learning (ICL) is now a common method for teaching large language models (LLMs) new tasks given labeled examples in the input context the LLM learns to perform the task without weight updates. Do models guided via ICL infer the underlying structure of the task defined by the context or do they rely on superficial heuristics that only generalize to identically distributed examples We address this question using transformations tasks and an NLI task that assess sensitivity to syntax 45; a requirement for robust language understanding. We further investigate whether out45;of45;distribution generalization can be improved via chain45;of45;thought prompting where the model is provided with a sequence of intermediate computation steps that illustrate how the task ought to be performed. In experiments with models from the GPT PaLM and Llama 2 families we find large variance across LMs. The variance is explained more by the composition of the pre45;training corpus and supervision methods than by model size; in particular models pre45;trained on code generalize better and benefit more from chain45;of45;thought prompting.
