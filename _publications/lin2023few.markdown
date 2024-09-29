---
layout: publication
title: Few-Shot Adaptation for Parsing Contextual Utterances with LLMs
authors: Lin Kevin, Xia Patrick, Fang Hao
conference: "Arxiv"
year: 2023
bibkey: lin2023few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10168"}
tags: ['Few Shot', 'Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
We evaluate the ability of semantic parsers based on large language models (LLMs) to handle contextual utterances. In real-world settings there typically exists only a limited number of annotated contextual utterances due to annotation cost resulting in an imbalance compared to non-contextual utterances. Therefore parsers must adapt to contextual utterances with a few training examples. We examine four major paradigms for doing so in conversational semantic parsing i.e. Parse-with-Utterance-History Parse-with-Reference-Program Parse-then-Resolve and Rewrite-then-Parse. To facilitate such cross-paradigm comparisons we construct SMCalFlow-EventQueries a subset of contextual examples from SMCalFlow with additional annotations. Experiments with in-context learning and fine-tuning suggest that Rewrite-then-Parse is the most promising paradigm when holistically considering parsing accuracy annotation cost and error types.
