---
layout: publication
title: 'Bigtranslate: Augmenting Large Language Models With Multilingual Translation Capability Over 100 Languages'
authors: Wen Yang, Chong Li, Jiajun Zhang, Chengqing Zong
conference: "Arxiv"
year: 2023
bibkey: yang2023augmenting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.18098'}
tags: ['Reinforcement Learning', 'GPT', 'Model Architecture', 'Training Techniques']
---
Large language models (LLMs) demonstrate promising translation performance
among various natural languages. However, many LLMs especially the open-sourced
ones, such as BLOOM and LLaMA, are English-dominant and support only dozens of
natural languages, making the potential of LLMs on language translation less
explored. In this work, we present BigTranslate which adapts LLaMA that covers
only 20 languages and enhances it with multilingual translation capability on
more than 100 languages. BigTranslate is built upon LLaMA-13B and it is
optimized in three steps. First, we continue training LLaMA with massive
Chinese monolingual data. Second, we continue training the model with a
large-scale parallel dataset that covers 102 natural languages. Third, we
instruct-tune the foundation model with multilingual translation instructions,
leading to our BigTranslate model. The preliminary experiments on multilingual
translation show that BigTranslate performs comparably with ChatGPT and Google
Translate in many languages and even outperforms ChatGPT in 8 language pairs.
We release the BigTranslate model and hope it can advance the research
progress.
