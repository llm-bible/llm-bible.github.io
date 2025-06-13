---
layout: publication
title: 'Prompting Open-source And Commercial Language Models For Grammatical Error Correction Of English Learner Text'
authors: Christopher Davis, Andrew Caines, Øistein Andersen, Shiva Taslimipoor, Helen Yannakoudakis, Zheng Yuan, Christopher Bryant, Marek Rei, Paula Buttery
conference: "Arxiv"
year: 2024
bibkey: davis2024prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07702"}
tags: ['GPT', 'Model Architecture', 'Reinforcement Learning', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Thanks to recent advances in generative AI, we are able to prompt large
language models (LLMs) to produce texts which are fluent and grammatical. In
addition, it has been shown that we can elicit attempts at grammatical error
correction (GEC) from LLMs when prompted with ungrammatical input sentences. We
evaluate how well LLMs can perform at GEC by measuring their performance on
established benchmark datasets. We go beyond previous studies, which only
examined GPT* models on a selection of English GEC datasets, by evaluating
seven open-source and three commercial LLMs on four established GEC benchmarks.
We investigate model performance and report results against individual error
types. Our results indicate that LLMs do not always outperform supervised
English GEC models except in specific contexts -- namely commercial LLMs on
benchmarks annotated with fluency corrections as opposed to minimal edits. We
find that several open-source models outperform commercial ones on minimal edit
benchmarks, and that in some settings zero-shot prompting is just as
competitive as few-shot prompting.
