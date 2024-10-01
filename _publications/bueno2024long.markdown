---
layout: publication
title: 'Lissard: Long And Simple Sequential Reasoning Datasets'
authors: Bueno Mirelle, Lotufo Roberto, Nogueira Rodrigo
conference: "Arxiv"
year: 2024
bibkey: bueno2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07859"}
  - {name: "Code", url: "https://github.com/unicamp-dl/Lissard"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Language models are now capable of solving tasks that require dealing with long sequences consisting of hundreds of thousands of tokens. However, they often fail on tasks that require repetitive use of simple rules, even on sequences that are much shorter than those seen during training. For example, state-of-the-art LLMs can find common items in two lists with up to 20 items but fail when lists have 80 items. In this paper, we introduce Lissard, a benchmark comprising seven tasks whose goal is to assess the ability of models to process and generate wide-range sequence lengths, requiring repetitive procedural execution. Our evaluation of open-source (Mistral-7B and Mixtral-8x7B) and proprietary models (GPT-3.5 and GPT-4) show a consistent decline in performance across all models as the complexity of the sequence increases. The datasets and code are available at https://github.com/unicamp-dl/Lissard
