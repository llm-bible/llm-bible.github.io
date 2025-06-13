---
layout: publication
title: 'Time Machine GPT'
authors: Felix Drinkall, Eghbal Rahimikia, Janet B. Pierrehumbert, Stefan Zohren
conference: "Arxiv"
year: 2024
bibkey: drinkall2024time
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.18543'}
tags: ['Training Techniques', 'Pre-Training', 'Model Architecture', 'GPT']
---
Large language models (LLMs) are often trained on extensive, temporally
indiscriminate text corpora, reflecting the lack of datasets with temporal
metadata. This approach is not aligned with the evolving nature of language.
Conventional methods for creating temporally adapted language models often
depend on further pre-training static models on time-specific data. This paper
presents a new approach: a series of point-in-time LLMs called Time Machine GPT
(TiMaGPT), specifically designed to be nonprognosticative. This ensures they
remain uninformed about future factual information and linguistic changes. This
strategy is beneficial for understanding language evolution and is of critical
importance when applying models in dynamic contexts, such as time-series
forecasting, where foresight of future information can prove problematic. We
provide access to both the models and training datasets.
