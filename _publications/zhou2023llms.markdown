---
layout: publication
title: 'Llms Learn Task Heuristics From Demonstrations: A Heuristic-driven Prompting Strategy For Document-level Event Argument Extraction'
authors: Zhou Hanzhang, Qian Junlang, Feng Zijian, Lu Hui, Zhu Zixiao, Mao Kezhi
conference: "Arxiv"
year: 2023
bibkey: zhou2023llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.06555"}
tags: ['Few Shot', 'In Context Learning', 'Prompting']
---
In this study, we investigate in-context learning (ICL) in document-level
event argument extraction (EAE) to alleviate the dependency on large-scale
labeled data for this task. We introduce the Heuristic-Driven Link-of-Analogy
(HD-LoA) prompting to address the challenge of example selection and to develop
a prompting strategy tailored for EAE. Specifically, we hypothesize and
validate that LLMs learn task-specific heuristics from demonstrations via ICL.
Building upon this hypothesis, we introduce an explicit heuristic-driven
demonstration construction approach, which transforms the haphazard example
selection process into a methodical method that emphasizes task heuristics.
Additionally, inspired by the analogical reasoning of human, we propose the
link-of-analogy prompting, which enables LLMs to process new situations by
drawing analogies to known situations, enhancing their performance on unseen
classes beyond limited ICL examples. Experiments show that our method
outperforms existing prompting methods and few-shot supervised learning methods
on document-level EAE datasets. Additionally, the HD-LoA prompting shows
effectiveness in diverse tasks like sentiment analysis and natural language
inference, demonstrating its broad adaptability.
