---
layout: publication
title: 'Efficiently Adapting Pretrained Language Models To New Languages'
authors: Zoltan Csaki, Pian Pawakapan, Urmish Thakker, Qiantong Xu
conference: "Arxiv"
year: 2023
bibkey: csaki2023efficiently
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05741"}
tags: ['Training Techniques', 'Efficiency and Optimization']
---
Recent large language models (LLM) exhibit sub-optimal performance on
low-resource languages, as the training data of these models is usually
dominated by English and other high-resource languages. Furthermore, it is
challenging to train models for low-resource languages, especially from
scratch, due to a lack of high quality training data. Adapting pretrained LLMs
reduces the need for data in the new language while also providing cross
lingual transfer capabilities. However, naively adapting to new languages leads
to catastrophic forgetting and poor tokenizer efficiency. In this work, we
study how to efficiently adapt any existing pretrained LLM to a new language
without running into these issues. In particular, we improve the encoding
efficiency of the tokenizer by adding new tokens from the target language and
study the data mixing recipe to mitigate forgetting. Our experiments on
adapting an English LLM to Hungarian and Thai show that our recipe can reach
better performance than open source models on the target language, with minimal
regressions on English.
