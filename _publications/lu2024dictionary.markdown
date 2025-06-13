---
layout: publication
title: 'Dictionary Insertion Prompting For Multilingual Reasoning On Multilingual Large Language Models'
authors: Hongyuan Lu, Zixuan Li, Wai Lam
conference: "Arxiv"
year: 2024
bibkey: lu2024dictionary
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01141"}
tags: ['Training Techniques', 'Prompting', 'Reinforcement Learning']
---
As current training data for Large Language Models (LLMs) are dominated by
English corpus, they are English-centric and they present impressive
performance on English reasoning tasks.\footnote\{This paper primarily studies
English-centric models, but our method could be universal by using the centric
language in the dictionary for non-English-centric LLMs.\} Yet, they usually
suffer from lower performance in other languages. There are about 7,000
languages over the world, and many are low-resourced on English-centric LLMs.
For the sake of people who primarily speak these languages, it is especially
urgent to enable our LLMs in those languages. Model training is usually
effective, but computationally expensive and requires experienced NLP
practitioners. This paper presents a novel and simple yet effective method
called \textbf\{D\}ictionary \textbf\{I\}nsertion \textbf\{P\}rompting
(\textbf\{DIP\}). When providing a non-English prompt, DIP looks up a word
dictionary and inserts words' English counterparts into the prompt for LLMs. It
then enables better translation into English and better English model thinking
steps which leads to obviously better results. We experiment with about 200
languages from FLORES-200. Since there are no adequate datasets, we use the
NLLB translator to create synthetic multilingual benchmarks from the existing 4
English reasoning benchmarks such as GSM8K and AQuA. Despite the simplicity and
computationally lightweight, we surprisingly found the effectiveness of DIP on
math and commonsense reasoning tasks on multiple open-source and close-source
LLMs.\footnote\{Our dictionaries, code, and synthetic benchmarks will be
open-sourced to facilitate future research.\}
