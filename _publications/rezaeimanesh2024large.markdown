---
layout: publication
title: 'Large Language Models For Persian \( \leftrightarrow \) English Idiom Translation'
authors: Sara Rezaeimanesh, Faezeh Hosseini, Yadollah Yaghoobzadeh
conference: "Arxiv"
year: 2024
bibkey: rezaeimanesh2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.09993"}
tags: ['BERT', 'Prompting', 'Applications', 'Model Architecture']
---
Large language models (LLMs) have shown superior capabilities in translating
figurative language compared to neural machine translation (NMT) systems.
However, the impact of different prompting methods and LLM-NMT combinations on
idiom translation has yet to be thoroughly investigated. This paper introduces
two parallel datasets of sentences containing idiomatic expressions for
Persian\\(\rightarrow\\)English and English\\(\rightarrow\\)Persian translations, with
Persian idioms sampled from our PersianIdioms resource, a collection of 2,200
idioms and their meanings, with 700 including usage examples. Using these
datasets, we evaluate various open- and closed-source LLMs, NMT models, and
their combinations. Translation quality is assessed through idiom translation
accuracy and fluency. We also find that automatic evaluation methods like
LLM-as-a-judge, BLEU, and BERTScore are effective for comparing different
aspects of model performance. Our experiments reveal that Claude-3.5-Sonnet
delivers outstanding results in both translation directions. For
English\\(\rightarrow\\)Persian, combining weaker LLMs with Google Translate
improves results, while Persian\\(\rightarrow\\)English translations benefit from
single prompts for simpler models and complex prompts for advanced ones.
